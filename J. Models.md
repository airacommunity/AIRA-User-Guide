# Overview  <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e">


An AIRA model refers to a computational feature designed within the AIRA platform to facilitate predictive analytics, automation, and intelligent decision-making. These models utilize various machine learning algorithms and data analysis techniques to process input data, generate insights, and produce actionable predictions.

> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

### Key Components of an AIRA Model:

-   **Input Data:** AIRA models require input data, which can be in the form of structured datasets such as CSV, Excel files. This data serves as the foundation for training and generating predictions.
-   **Training Phase:** During the training phase, the model learns patterns and relationships within the input data. This involves selecting appropriate features and defining the target variable for prediction. The model is trained using machine learning algorithms to optimize its predictive capabilities.
-   **Prediction Phase:** Once trained, the model can be used to make predictions on new or unseen data. Users can input feature values into the model to obtain predictive results. Additionally, datasets can be uploaded for batch prediction tasks.
-   **Deployment:** After satisfactory performance during the prediction phase, the model can be deployed for operational use within the AIRA platform. Deployment involves providing a name for the model and confirming the deployment process.
-   **Integration:** Deployed models can be seamlessly integrated into various workflows and applications within the AIRA platform. They serve as powerful tools for automation, intelligence, and optimization, enhancing operational efficiency and decision-making processes.

## How to Create an AIRA Model

1.  **Navigate to Model Section:**
    -   Go to the left navigation menu and click on the "Model" option. This action will open the model window.
2.  **Search Existing Models (Optional):**
    -   In the model section, there is a search bar available. Use this search bar to find any previously uploaded or created models if needed.
3.  **Create a New Model:**
    -   To create a new model, click on the Add New Model > Create New Model button.
4.  **Enter Model Name:**
    -   A window will appear prompting you to enter a name for your new model
5.  **Connect Training Dataset:**
    -   The first step is to connect the training dataset. Click on the upload button and select your dataset. AIRA models accept datasets in CSV or Excel format.
    -   After selecting the dataset, the data distribution chart and data table will be shown in the "Connect Training Data" section.
    -   After uploading data set, user can change the data type of columns in (Numberic, Date Time, ID , Text, Categorical Etc)
    -   If needed, you can change the dataset by clicking on the "Change" button.
6.  **Proceed to Model Training:**
    -   After connecting the dataset, click on the "Next" button to move forward.
    -   In the model training section, identify the target and features of the dataset for training the model.
7.  **Start Training:**
    -   Once you have selected the target and features, click on the "Start Training" button to begin the model training process.
8.  **Review Model Summary:**
    -   After training, a summary of the model, top fields, and dataset will be displayed.
    -   Click on the next button to test the prediction of the model.
9.  **Fill in Feature Values for Prediction:**
    -   To get predictive results, fill in feature values. You can also upload feature values using the "Upload" option.
10.  **Submit Prediction:**
    -   After filling in the feature values, click on the "Submit" button for prediction. It shows the predicted target value.
11.  **Deploy the Model:**
    -   If satisfied with the prediction results, click on deploy dropdown, provide an activity name and click on the "Deploy" button located below.
12.  **Model Deployment Confirmation:**
    -   Your model is now deployed and ready for use in your AIRA workflows.

## Upload Model In AIRA

As an example, let's consider a linear regression model that takes two input features, "one" and "two", and returns an output value based on these inputs.

**1. Create Zip:** Create a zip file name main.zip include model file and main.py

**2. Model File:** Serialise your trained machine learning model into a pickle/folder/json file, In this example we are creating a pickle file. This file will allow you to save and load your model within the AIRA platform.

**3. Create Main.py:** Within the zip file, include a main.py file. This file will serve as the entry point for running your model within the AIRA platform.

### Steps To Creating "main.py" File - Related to Current Example

#### Step 1 : Import Dependencies

Within the main.py file, import all the necessary dependencies required for your machine learning model.

```js

# For Current Example

import numpy as np
import pickle
import argparse
import base64
import json
```

#### Step 2 : Define Prediction Function

In the main.py file, create a function named predict that takes input features and the path to the model as arguments.

```js
def use_model(inp_features, model_path):

    # Load the trained model from the pickle file
    model = pickle.load(open(model_path, 'rb'))

    # Perform prediction on the input features
    prediction = model.predict(inp_features)

    # Round the prediction to two decimal places
    output = round(prediction[0], 2)

    # Print the output value
    print(output)

    # Return the predicted output
    return output
```

**Explanation**

-   The use_model function takes two arguments: inp_features, which represents the input features for prediction, and model_path, which specifies the path to the trained model file.
-   It loads the trained machine learning model from the specified pickle file using the pickle.load() function.
-   Then, it performs prediction on the input features using the loaded model and stores the result in the prediction variable.
-   The predicted value is rounded to two decimal places using the round() function and stored in the output variable.
-   The predicted output is printed to the console using the print() function.
-   Finally, the predicted output is returned from the function.

#### Step 3 : Entry Point Function

In the main.py file, create a function named main that serves as the entry point of the script.

```js
def main():
    # Parse command-line arguments
    ap = argparse.ArgumentParser()
    ap.add_argument("-i", "--input", required=True, help="Input Feature JSON")
    ap.add_argument("-m", "--mpath", required=True, help="Path to Model")
    args = vars(ap.parse_args())

    # Decode and parse the input JSON
    input_passed_encoded = args['input']
    input_passed_decoded = base64.b64decode(input_passed_encoded).decode('utf-8')
    input_passed_decoded_dict = json.loads(input_passed_decoded)
    input_passed_decoded_dict = next(iter(input_passed_decoded_dict.values()))
    input_passed_decoded_dict = json.loads(input_passed_decoded_dict)

    # Extract input features in the required order
    feature_ordered_list = ["one", "two"]
    input_list = [input_passed_decoded_dict[i] for i in feature_ordered_list]

    # Load the model and make predictions
    model_path = args['mpath'] + 'model.pkl'
    use_mode([input_list], model_path)
```

**Explanation**

-   The main function is defined to handle the main execution logic of the script.
-   It starts by setting up command-line argument parsing using the argparse module, defining two required arguments: -i for input feature JSON and -m for the path to the model.
-   Command-line arguments are parsed and stored in the args dictionary using the vars() function.
-   The input feature JSON is decoded from base64 encoding and parsed into a Python dictionary using the base64 and json modules.
-   The input features are extracted from the dictionary in the required order specified by feature_ordered_list.
-   The path to the model file is constructed by appending 'model.pkl' to the specified model directory path.
-   Finally, the use_model function is called with the input features and model path to make predictions.

#### Step 4 : Condition for Main Function Call

Below the definition of the main function, add a conditional statement to check if the script is being run directly as the main module.

```js
if __name__ == "__main__":
    main()
```

**Explanation:**

-   The if **name** == "**main**": statement checks if the script is being executed directly by the Python interpreter as the main module.
-   If the condition is True, indicating that the script is the main module, the main() function is called to initiate the execution of the script.
-   This conditional statement ensures that the main() function is only called when the script is executed directly, not when it is imported as a module into another script.

**Purpose:**

-   By wrapping the call to the main() function inside this conditional statement, you ensure that the script's main functionality is executed only when the script is run directly.
-   This allows the script to be reusable and importable as a module in other scripts without automatically triggering its main functionality.

#### Step 5 : Packaging Main Script and Model File

With the main.py script finalised and the model file containing the trained model, both files are bundled together into a single zip archive for easy distribution and deployment.

This point highlights the action of packaging both the script and the model into a convenient zip file, ensuring that they can be easily transported, shared, and deployed across different environments or systems.

## Steps To Upload Model In AIRA

**1. Navigate to the Model Upload Section**

Open the AIRA platform and locate the model upload section. Click on it to proceed.

**2. Add New Model**

Click on the "Add new model" option to initiate the model upload process.

**3. Enter Model Name**

Provide a name for the model in the designated section and click on the "Upload Existing Model" button.

**4. Upload Zip File**

Select the zip file containing the main.py script and the model.pkl file. You can either drag and drop the file or use the upload button.

**5. Add Model Description**

Enter a short description of the model in the provided field and click on the "Next" button.

**6. Define Model Inputs**

Specify the inputs required for the model. This includes the input type, name, label, regex validation (if applicable), and whether it's required. Click on the "Next" button to proceed.

**Adding Model Inputs:**

-   **Type:** Select the type of input data. For this example, choose "JSON" as the input type.
-   **Name:** Use the same name as the parameter in the predict function. In this case, name it "inp_feature."
-   **Label:** Assign a label to the input. Since we're using the same name, label it as "inp_feature" as well.
-   **Regex Validation:** If required, enter a regular expression for validation purposes.
-   **Required:** Specify whether this input is required for the model. For this example, select "Yes."
-   **Action:** Use the "add" action to add the input. You can also delete inputs if needed. Click on the "Next" button to proceed.

**7. Define Model Outputs**

Define the outputs of the model, including type, name, label, and description. Click on the "Next" button to continue.

**Adding Model Output:**

-   **Type:** Define the type of output data. Since we're predicting a value, select the appropriate type.
-   **Name:** Assign the same name as the output parameter in the predict function. In this case, name it "predict."
-   **Label:** Use "predict" as the label for the output.
-   **Description:** Provide a brief description of the output.
-   **Action:** Use the "add" action to add the output. You can also delete outputs if needed. Click on the "Next" button to continue.

**8. Deployment Section**

**Edit File Content**

After clicking on the next button, the model deployment window opens. In the first option, you can edit the content of the main.py file. This allows you to make any necessary changes or updates to the Python script before deploying the model.

**Input Section**

In this section, you can check if your model is running properly by providing input data. Enter the required input in the designated field and click on the "Generate Output" button. The predicted value will be displayed in the output section.

**Output Section**

This section displays the output generated by the model based on the provided input data.

**Deployment Section**

Here, you need to enter the specific activity name in the respective field. This could be the name of the task or activity associated with deploying the model. Once you've entered the activity name, click on the "Deployment" button to deploy the model on the AIRA platform.

----

![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
