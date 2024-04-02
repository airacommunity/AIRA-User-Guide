![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# Intelligent Document Processing <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">

## Overview
Welcome to the AIRA Intelligent Document Processing (IDP) User Guide! This section will walk you through the steps of using the IDP function within AIRA, providing you with a seamless and efficient experience in handling document-related tasks. To know how to use IDP in AIRA Workflow visit AIRA IDP App.

The Intelligent Document Processing (IDP) module within the workflow plays a pivotal role in automating processes that involve extracting data from files. IDP is specifically designed to efficiently extract relevant information from documents, facilitating a streamlined and automated workflow. By incorporating the IDP module, users can harness the power of automation to accurately and swiftly process data from files, enhancing the overall efficiency of their business processes. This module serves as a crucial component in automating document-centric tasks, reducing manual efforts, and ensuring accuracy in data extraction processes.

<br>

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-caution.jpg?raw=true"> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

<br>

## Steps To Create Learning Instance

### 1. Accessing IDP Learning Instance

  - Scroll down the left navigation panel of AIRA.
  - Click on the "IDP" section. Upon clicking the IDP,  the Learning Instance window will open.
  - Utilise the search bar at the top right corner to quickly locate and access previous instances within AIRA.

### 2. Create New Learning Instance

  - To create a new instance, locate and click the "Add New Instance" button in the learning Instance window.
  - In the "Learning Instance Name" section, assign a unique name to your instance.
  - Find the "Drop File" section below the "Learning Instance Name." Upload files into this section by dragging and dropping or browsing. Supported file formats include JPG, JPEG, PNG, and PDF.
  - Click on "Create" to initiate the instance creation process.

### 3. Select Document Type

  - Locate the dropdown button situated next to deploy button.
  - Click on the dropdown button to reveal a list of document formats, such as "Form," "Invoice," and others.
  - Choose the appropriate document type from the available options.

### 4. Extract Document Data

  - Choose the "Extract Data" button to extract information from the documents.
  - This action triggers the extraction process, capturing all available textual data within the documents.
  - Add Custom Rule if data is not extracted or errors occur during the data extraction of any field.

#### Add New Field

- If any field is not automatically extracted, navigate to the "Field" section.
- Within the Field section, you'll find two options: Field Labels and Field Name.
- Fill in the "Field Labels" section with the desired name for the selected field.
- In the "Field Name" section, specify the actual field name you are looking for.
- Click on the "Add" button to apply the new fields.
- Finally, click on the "Extract Data" button to extract all the fields.
- Add Custom Rule if data is not extracted properly.


#### Add Custom Rule

In the event that some data is not extracted or errors occur during the data extraction of any field, AIRA provides the option to add custom rules for more precise extraction. Here's how to utilise the "Add Custom Rule" option:

  - Identify the field where extraction errors or omissions have occurred.
  - Navigate to the bottom right side of the field and click on the "Add Custom Rule" option.
  - A new window will pop up, displaying the OCR-processed text for the selected field.
  - Below the OCR text, a "Custom Rule Bar" is available for setting exact data rules.
  - In the Custom Rule Bar, the first section is for filling in the "Search Item." Identify the item that helps locate the field that you want to extract. 
  - The next section allows you to set the logic for the custom rule. Define the logic based on the specific issue. List of logic is given below :
    - Find Text In Next Line
    - Find Next Text On Same Line
    - Find Previous Text On Same Line
    - Find Next Word On Same Line
    - Start With Keyword
    - Contain Keyword
    - Next N Line
    - Previous N Line
    - Next Specific Line
    - Find Previous Specific Line
    - Find Specific Words Start to End
- Click on the "Apply Rule" button to apply the custom rule to the selected field.
- If needed, additional rules can be added by clicking the "Add Rule" button.
- Rules can be deleted by clicking the "Delete" button.

<br>

> For example: 
> - The issue is related to the "Customer Name" field, and the Bill Number is just above the “Customer Name,” so the search item is Bill Number.
> - According to our example, the logic for the custom rule is Find Text in the Next Line.

<br>

### 5. Extract Table

- Beneath the "Extract Data" section, locate the "Extract Table" section.
- Click on the "Extract Table" button within the Table Extraction section.
- A new window will appear, displaying the extracted table on the right side.
- Navigate to the right section of the window and click on the table of interest.
- The data of the selected table will be displayed in the lower part of the window.
- To download the desired table, click on the download button next to the "Confirm Table" button.
- Once you've selected the table, confirm your choice by clicking the "Confirm Table" button.

### 6. Additional Setting

Click on the setting button located at the top right side of the window. It helps to create the document image.There are three options available in the settings :

- Grey Scale: When toggled on, it converts the document color to grayscale.
- Binarization: Converts the grayscale document into black and white. It requires two parameters:
  - Max: Its limit is 255. If we select a maximum value (e.g., 180), grayscale values above this threshold convert into white.
  - Threshold: Its limit is 255. If we select a threshold value (e.g., 180), grayscale values lower than this threshold convert into black.
- Noise Deduction: When toggled on, it enhances the picture quality by reducing noise.
- After applying all the required setting click on the apply button to save and execute.

### 7. Deploying the Learning Instance

- Confirm that all data extraction processes have been executed accurately.
- Review the extracted information to ensure completeness and correctness.
- Navigate to the top right corner of the window.
- Click on the "Deploy Instance" button.
- Upon clicking, the learning instance is deployed, making it available for use within the AIRA workflow.
- The instance is now ready to contribute to the automation and efficiency of your document processing tasks.

### Conclusion

As we conclude this section, envision the powerful fusion of Intelligent Document Processing with AIRA. The insights gained here pave the way for transforming document-related challenges into opportunities, unlocking new dimensions of efficiency and automation within your workflows.

----

> To proceed with your exploration, just click the 'Next' button to seamlessly move on to the next section.

----


<table align="right" border="0">
    <tr>
      <td align="center"><a href="https://github.com/airacommunity/AIRA-User-Guide/blob/main/A.%20Introduction%20to%20AIRA%20User%20Guide.md"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-previous.png" alt="Image 5" width="40" height="40"></a></td>
      <td align="center"><a href="https://github.com/airacommunity/AIRA-User-Guide/blob/main/C.%20Introduction%20to%20AIRA%20Installation.md"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-next.png" alt="Image 5" width="40" height="40"></a></td>
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
