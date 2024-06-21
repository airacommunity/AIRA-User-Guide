<h1><span style="color: #411d66;">Overview                                                    <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e"></span></h1>

An AIRA model refers to a computational feature designed within the AIRA platform to facilitate predictive analytics, automation, and intelligent decision-making. These models utilize various machine learning algorithms and data analysis techniques to process input data, generate insights, and produce actionable predictions.
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h3 id="key-components-of-an-aira-model" class="toc-header">Key Components of an AIRA Model:</h3>
<ul>
 	<li><strong>Input Data:</strong> AIRA models require input data, which can be in the form of structured datasets such as CSV, Excel files. This data serves as the foundation for training and generating predictions.</li>
 	<li><strong>Training Phase:</strong> During the training phase, the model learns patterns and relationships within the input data. This involves selecting appropriate features and defining the target variable for prediction. The model is trained using machine learning algorithms to optimize its predictive capabilities.</li>
 	<li><strong>Prediction Phase:</strong> Once trained, the model can be used to make predictions on new or unseen data. Users can input feature values into the model to obtain predictive results. Additionally, datasets can be uploaded for batch prediction tasks.</li>
 	<li><strong>Deployment:</strong> After satisfactory performance during the prediction phase, the model can be deployed for operational use within the AIRA platform. Deployment involves providing a name for the model and confirming the deployment process.</li>
 	<li><strong>Integration:</strong> Deployed models can be seamlessly integrated into various workflows and applications within the AIRA platform. They serve as powerful tools for automation, intelligence, and optimization, enhancing operational efficiency and decision-making processes.</li>
</ul>
<h2 id="how-to-create-an-aira-model" class="toc-header">How to Create an AIRA Model</h2>
<ol>
 	<li><strong>Navigate to Model Section:</strong>
<ul>
 	<li>Go to the left navigation menu and click on the "Model" option. This action will open the model window.</li>
</ul>
</li>
 	<li><strong>Search Existing Models (Optional):</strong>
<ul>
 	<li>In the model section, there is a search bar available. Use this search bar to find any previously uploaded or created models if needed.</li>
</ul>
</li>
 	<li><strong>Create a New Model:</strong>
<ul>
 	<li>To create a new model, click on the Add New Model &gt; Create New Model button.</li>
</ul>
</li>
 	<li><strong>Enter Model Name:</strong>
<ul>
 	<li>A window will appear prompting you to enter a name for your new model</li>
</ul>
</li>
 	<li><strong>Connect Training Dataset:</strong>
<ul>
 	<li>The first step is to connect the training dataset. Click on the upload button and select your dataset. AIRA models accept datasets in CSV or Excel format.</li>
 	<li>After selecting the dataset, the data distribution chart and data table will be shown in the "Connect Training Data" section.</li>
 	<li>After uploading data set, user can change the data type of columns in (Numberic, Date Time, ID , Text, Categorical Etc)</li>
 	<li>If needed, you can change the dataset by clicking on the "Change" button.</li>
</ul>
</li>
 	<li><strong>Proceed to Model Training:</strong>
<ul>
 	<li>After connecting the dataset, click on the "Next" button to move forward.</li>
 	<li>In the model training section, identify the target and features of the dataset for training the model.</li>
</ul>
</li>
 	<li><strong>Start Training:</strong>
<ul>
 	<li>Once you have selected the target and features, click on the "Start Training" button to begin the model training process.</li>
</ul>
</li>
 	<li><strong>Review Model Summary:</strong>
<ul>
 	<li>After training, a summary of the model, top fields, and dataset will be displayed.</li>
 	<li>Click on the next button to test the prediction of the model.</li>
</ul>
</li>
 	<li><strong>Fill in Feature Values for Prediction:</strong>
<ul>
 	<li>To get predictive results, fill in feature values. You can also upload feature values using the "Upload" option.</li>
</ul>
</li>
 	<li><strong>Submit Prediction:</strong>
<ul>
 	<li>After filling in the feature values, click on the "Submit" button for prediction. It shows the predicted target value.</li>
</ul>
</li>
 	<li><strong>Deploy the Model:</strong>
<ul>
 	<li>If satisfied with the prediction results, click on deploy dropdown, provide an activity name and click on the "Deploy" button located below.</li>
</ul>
</li>
 	<li><strong>Model Deployment Confirmation:</strong>
<ul>
 	<li>Your model is now deployed and ready for use in your AIRA workflows.</li>
</ul>
</li>
</ol>
<h2 id="upload-model-in-aira" class="toc-header">Upload Model In AIRA</h2>
As an example, let's consider a linear regression model that takes two input features, "one" and "two", and returns an output value based on these inputs.

<strong>1. Create Zip:</strong> Create a zip file name main.zip include model file and main.py

<strong>2. Model File:</strong> Serialise your trained machine learning model into a pickle/folder/json file, In this example we are creating a pickle file. This file will allow you to save and load your model within the AIRA platform.

<strong>3. Create Main.py:</strong> Within the zip file, include a main.py file. This file will serve as the entry point for running your model within the AIRA platform.
<h3 id="steps-to-creating-mainpy-file-related-to-current-example" class="toc-header">Steps To Creating "main.py" File - Related to Current Example</h3>
<h4 id="step-1-import-dependencies" class="toc-header">Step 1 : Import Dependencies</h4>
Within the main.py file, import all the necessary dependencies required for your machine learning model.
<div class="code-toolbar">
<pre class="prismjs line-numbers language-js"><code class="language-js">
# For Current Example

import numpy as np
import pickle
import argparse
import base64
import json</code></pre>
</div>
<h4 id="step-2-define-prediction-function" class="toc-header">Step 2 : Define Prediction Function</h4>
In the main.py file, create a function named predict that takes input features and the path to the model as arguments.
<div class="code-toolbar">
<pre class="prismjs line-numbers language-js"><code class="language- language-js">def predict(inp_features, model_path):

    # Load the trained model from the pickle file
    model = pickle.load(open(model_path, 'rb'))

    # Perform prediction on the input features
    prediction = model.predict(inp_features)

    # Round the prediction to two decimal places
    output = round(prediction[0], 2)

    # Print the output value
    print(output)

    # Return the predicted output
    return output</code></pre>
</div>
<strong>Explanation</strong>
<ul>
 	<li>The predict function takes two arguments: inp_features, which represents the input features for prediction, and model_path, which specifies the path to the trained model file.</li>
 	<li>It loads the trained machine learning model from the specified pickle file using the pickle.load() function.</li>
 	<li>Then, it performs prediction on the input features using the loaded model and stores the result in the prediction variable.</li>
 	<li>The predicted value is rounded to two decimal places using the round() function and stored in the output variable.</li>
 	<li>The predicted output is printed to the console using the print() function.</li>
 	<li>Finally, the predicted output is returned from the function.</li>
</ul>
<h4 id="step-3-entry-point-function" class="toc-header">Step 3 : Entry Point Function</h4>
In the main.py file, create a function named main that serves as the entry point of the script.
<div class="code-toolbar">
<pre class="prismjs line-numbers language-js"><code class="language- language-js">def main():
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
    predict([input_list], model_path)</code></pre>
</div>
<strong>Explanation</strong>
<ul>
 	<li>The main function is defined to handle the main execution logic of the script.</li>
 	<li>It starts by setting up command-line argument parsing using the argparse module, defining two required arguments: -i for input feature JSON and -m for the path to the model.</li>
 	<li>Command-line arguments are parsed and stored in the args dictionary using the vars() function.</li>
 	<li>The input feature JSON is decoded from base64 encoding and parsed into a Python dictionary using the base64 and json modules.</li>
 	<li>The input features are extracted from the dictionary in the required order specified by feature_ordered_list.</li>
 	<li>The path to the model file is constructed by appending 'model.pkl' to the specified model directory path.</li>
 	<li>Finally, the predict function is called with the input features and model path to make predictions.</li>
</ul>
<h4 id="step-4-condition-for-main-function-call" class="toc-header">Step 4 : Condition for Main Function Call</h4>
Below the definition of the main function, add a conditional statement to check if the script is being run directly as the main module.
<div class="code-toolbar">
<pre class="prismjs line-numbers language-js"><code class="language- language-js">if __name__ == "__main__":
    main()</code></pre>
</div>
<strong>Explanation:</strong>
<ul>
 	<li>The if <strong>name</strong> == "<strong>main</strong>": statement checks if the script is being executed directly by the Python interpreter as the main module.</li>
 	<li>If the condition is True, indicating that the script is the main module, the main() function is called to initiate the execution of the script.</li>
 	<li>This conditional statement ensures that the main() function is only called when the script is executed directly, not when it is imported as a module into another script.</li>
</ul>
<strong>Purpose:</strong>
<ul>
 	<li>By wrapping the call to the main() function inside this conditional statement, you ensure that the script's main functionality is executed only when the script is run directly.</li>
 	<li>This allows the script to be reusable and importable as a module in other scripts without automatically triggering its main functionality.</li>
</ul>
<h4 id="step-5-packaging-main-script-and-model-file" class="toc-header">Step 5 : Packaging Main Script and Model File</h4>
With the main.py script finalised and the model file containing the trained model, both files are bundled together into a single zip archive for easy distribution and deployment.

This point highlights the action of packaging both the script and the model into a convenient zip file, ensuring that they can be easily transported, shared, and deployed across different environments or systems.
<h2 id="steps-to-upload-model-in-aira" class="toc-header">Steps To Upload Model In AIRA</h2>
<strong>1. Navigate to the Model Upload Section</strong>

Open the AIRA platform and locate the model upload section. Click on it to proceed.

<strong>2. Add New Model</strong>

Click on the "Add new model" option to initiate the model upload process.

<strong>3. Enter Model Name</strong>

Provide a name for the model in the designated section and click on the "Upload Existing Model" button.

<strong>4. Upload Zip File</strong>

Select the zip file containing the main.py script and the model.pkl file. You can either drag and drop the file or use the upload button.

<strong>5. Add Model Description</strong>

Enter a short description of the model in the provided field and click on the "Next" button.

<strong>6. Define Model Inputs</strong>

Specify the inputs required for the model. This includes the input type, name, label, regex validation (if applicable), and whether it's required. Click on the "Next" button to proceed.

<strong>Adding Model Inputs:</strong>
<ul>
 	<li><strong>Type:</strong> Select the type of input data. For this example, choose "JSON" as the input type.</li>
 	<li><strong>Name:</strong> Use the same name as the parameter in the predict function. In this case, name it "inp_feature."</li>
 	<li><strong>Label:</strong> Assign a label to the input. Since we're using the same name, label it as "inp_feature" as well.</li>
 	<li><strong>Regex Validation:</strong> If required, enter a regular expression for validation purposes.</li>
 	<li><strong>Required:</strong> Specify whether this input is required for the model. For this example, select "Yes."</li>
 	<li><strong>Action:</strong> Use the "add" action to add the input. You can also delete inputs if needed. Click on the "Next" button to proceed.</li>
</ul>
<strong>7. Define Model Outputs</strong>

Define the outputs of the model, including type, name, label, and description. Click on the "Next" button to continue.

<strong>Adding Model Output:</strong>
<ul>
 	<li><strong>Type:</strong> Define the type of output data. Since we're predicting a value, select the appropriate type.</li>
 	<li><strong>Name:</strong> Assign the same name as the output parameter in the predict function. In this case, name it "predict."</li>
 	<li><strong>Label:</strong> Use "predict" as the label for the output.</li>
 	<li><strong>Description:</strong> Provide a brief description of the output.</li>
 	<li><strong>Action:</strong> Use the "add" action to add the output. You can also delete outputs if needed. Click on the "Next" button to continue.</li>
</ul>
<strong>8. Deployment Section</strong>

<strong>Edit File Content</strong>

After clicking on the next button, the model deployment window opens. In the first option, you can edit the content of the main.py file. This allows you to make any necessary changes or updates to the Python script before deploying the model.

<strong>Input Section</strong>

In this section, you can check if your model is running properly by providing input data. Enter the required input in the designated field and click on the "Generate Output" button. The predicted value will be displayed in the output section.

<strong>Output Section</strong>

This section displays the output generated by the model based on the provided input data.

<strong>Deployment Section</strong>

Here, you need to enter the specific activity name in the respective field. This could be the name of the task or activity associated with deploying the model. Once you've entered the activity name, click on the "Deployment" button to deploy the model on the AIRA platform.

&nbsp;

----

![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
