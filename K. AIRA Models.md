![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# AIRA Models <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">

## Overiview
An AIRA model refers to a computational framework designed within the AIRA platform to facilitate predictive analytics, automation, and intelligent decision-making. These models utilize various machine learning algorithms and data analysis techniques to process input data, generate insights, and produce actionable predictions.

<br>

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-caution.jpg?raw=true"> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

<br>


### Key Components of an AIRA Model:

- **Input Data:** AIRA models require input data, which can be in the form of structured datasets such as CSV, JSON, Excel files, or connected databases like Google Sheets, PostgreSQL, or MySQL. This data serves as the foundation for training and generating predictions.
- **Training Phase:** During the training phase, the model learns patterns and relationships within the input data. This involves selecting appropriate features and defining the target variable for prediction. The model is trained using machine learning algorithms to optimize its predictive capabilities.
- **Prediction Phase:** Once trained, the model can be used to make predictions on new or unseen data. Users can input feature values into the model to obtain predictive results. Additionally, datasets can be uploaded for batch prediction tasks.
- **Deployment:** After satisfactory performance during the prediction phase, the model can be deployed for operational use within the AIRA platform. Deployment involves providing a name for the model and confirming the deployment process.
- **Integration:** Deployed models can be seamlessly integrated into various workflows and applications within the AIRA platform. They serve as powerful tools for automation, intelligence, and optimization, enhancing operational efficiency and decision-making processes.

## How to Create an AIRA Model

1. **Navigate to Model Section:**
   - Go to the left navigation menu and click on the "Model" option. This action will open the model window.

2. **Search Existing Models (Optional):**
   - In the model section, there is a search bar available. Use this search bar to find any previously uploaded or created models if needed.

3. **Create a New Model:**
   - To create a new model, click on the "Create New Model" button.

4. **Enter Model Name:**
   - A window will appear prompting you to enter a name for your new model. Provide a descriptive name for your model.

5. **Confirm Model Creation and Open:**
   - Click on the "Create New Model" button to confirm the creation of your model.
   - Search for the model by its name in the model section and click on it to open.

6. **Connect Training Dataset:**
   - The first step is to connect the training dataset. Click on the upload button and select your dataset. AIRA models accept datasets in CSV or Excel format.
   - After selecting the dataset, the data distribution chart and data table will be shown in the "Connect Training Data" section.
   - After uploading data set, user can change the data type of columns in (Numberic, Date Time, ID , Text, Categorical Etc)
   - If needed, you can change the dataset by clicking on the "Change" button.

7. **Proceed to Model Training:**
   - After connecting the dataset, click on the "Next" button to move forward.
   - In the model training section, identify the target and features of the dataset for training the model.

8. **Start Training:**
   - Once you have selected the target and features, click on the "Start Training" button to begin the model training process.

9. **Review Model Summary:**
   - After training, a summary of the model, top fields, and dataset will be displayed.

10. **Fill in Feature Values for Prediction:**
    - To get predictive results, fill in feature values. You can upload feature values using the "Upload" option.

11. **Submit Prediction:**
    - After filling in the feature values, click on the "Submit" button for prediction.

12. **Deploy the Model:**
    - If satisfied with the prediction results, Provide an activity name and click on the "Deploy" button located below.

13. **Model Deployment Confirmation:**
    - Your model is now deployed and ready for use in your AIRA workflows.


As we wrap up this section, envision with me the transformative power that models bring to AIRA. The knowledge gained here sets the stage for us to leverage models as catalysts for automation, intelligence, and operational excellence within your AIRA-driven workflows.

## How to upload Model In AIRA

As an example, let's consider a linear regression model that takes two input features, "one" and "two", and returns an output value based on these inputs. 

**Create File:** Serialise your trained machine learning model into a pickle/folder/json/pdf file, In this example we are creating a pickle file. This file will allow you to save and load your model within the AIRA platform.

**Create Main.py:** Within the zip file, include a main.py file. This file will serve as the entry point for running your model within the AIRA platform.

### Steps To Creating "main.py" File - Related to Current Example

#### Step 1 : Import Dependencies

Within the main.py file, import all the necessary dependencies required for your machine learning model.

```
# For Current Example

import numpy as np
import pickle
import argparse
import base64
import json

```
#### Step 2 : Define Prediction Function

In the main.py file, create a function named predict that takes input features and the path to the model as arguments.

```

def predict(inp_features, model_path):
   
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

* The predict function takes two arguments: inp_features, which represents the input features for prediction, and model_path, which specifies the path to the trained model file.

* It loads the trained machine learning model from the specified pickle file using the pickle.load() function.

* Then, it performs prediction on the input features using the loaded model and stores the result in the prediction variable.

* The predicted value is rounded to two decimal places using the round() function and stored in the output variable.

* The predicted output is printed to the console using the print() function.

* Finally, the predicted output is returned from the function.

#### Step 3 : Entry Point Function

In the main.py file, create a function named outputs that serves as the entry point of the script.

```
def output():
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
    predict([input_list], model_path)

```
**Explanation**

* The output function is defined to handle the main execution logic of the script.

* It starts by setting up command-line argument parsing using the argparse module, defining two required arguments: -i for input feature JSON and -m for the path to the model.

* Command-line arguments are parsed and stored in the args dictionary using the vars() function.

* The input feature JSON is decoded from base64 encoding and parsed into a Python dictionary using the base64 and json modules.

* The input features are extracted from the dictionary in the required order specified by feature_ordered_list.

* The path to the model file is constructed by appending 'model.pkl' to the specified model directory path.

* Finally, the predict function is called with the input features and model path to make predictions.

#### Step 4 : Condition for Main Function Call

Below the definition of the main function, add a conditional statement to check if the script is being run directly as the main module.

```
if __name__ == "__main__":
    output()

```
**Explanation:**

* The if __name__ == "__main__": statement checks if the script is being executed directly by the Python interpreter as the main module.

* If the condition is True, indicating that the script is the main module, the output() function is called to initiate the execution of the script.

* This conditional statement ensures that the output() function is only called when the script is executed directly, not when it is imported as a module into another script.

**Purpose:**

* By wrapping the call to the output() function inside this conditional statement, you ensure that the script's main functionality is executed only when the script is run directly.

* This allows the script to be reusable and importable as a module in other scripts without automatically triggering its main functionality.

#### Step 5 : Packaging Main Script and Model File

With the main.py script finalised and the model file containing the trained model, both files are bundled together into a single zip archive for easy distribution and deployment.

This point highlights the action of packaging both the script and the model into a convenient zip file, ensuring that they can be easily transported, shared, and deployed across different environments or systems.

#### Step 6 : Steps To Upload Model In AIRA
----

<table align="right" border="0">
    <tr>
      <td align="center"><a href=""><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-previous.png" alt="Image 5" width="40" height="40"></a></td>
      <td align="center"><a href=""><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-next.png" alt="Image 5" width="40" height="40"></a></td>
    </tr>
</table>

<br>
<br>
<br>

<table border="0" align="center">
  <tr>
    <td align="center"><a href="https://aira.fr/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-website.png?raw=true" alt="Image 5" width="30" height="30"></a></td>
    <td><a href="https://www.linkedin.com/company/aira-rpa/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20linkedin.png?raw=true" alt="Image 1" width="30" height="30"></a></td>
    <td><a href="https://www.instagram.com/connect_aira/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-instagram.png?raw=true" alt="Image 2" width="30" height="30"></a></td>
    <td><a href="https://www.youtube.com/channel/UCHHCcwQrx-_19sAhu-2R4ww"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20youtube.png?raw=true" alt="Image 3" width="30" height="30"></a></td>
    <td><a href="https://twitter.com/Aira_RPA"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20twitter.png?raw=true" alt="Image 4" width="30" height="30"></a></td>
    <td><a href="mailto:connect@aira.fr"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20gmail.png?raw=true" alt="Image 6" width="30" height="30"></a></td>
  </tr>
</table>


![Footer](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/6bb25f04-ad9c-476c-b653-c3c1dac1a868)
