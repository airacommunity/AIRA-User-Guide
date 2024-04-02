# Intelligent Document Processing

## Overview
Welcome to the AIRA Intelligent Document Processing (IDP) User Guide! This section will walk you through the steps of using the IDP function within AIRA, providing you with a seamless and efficient experience in handling document-related tasks. To know how to use IDP in AIRA Workflow visit AIRA IDP App.

The Intelligent Document Processing (IDP) module within the workflow plays a pivotal role in automating processes that involve extracting data from files. IDP is specifically designed to efficiently extract relevant information from documents, facilitating a streamlined and automated workflow. By incorporating the IDP module, users can harness the power of automation to accurately and swiftly process data from files, enhancing the overall efficiency of their business processes. This module serves as a crucial component in automating document-centric tasks, reducing manual efforts, and ensuring accuracy in data extraction processes.

## Steps To Create Learning Instance

### 1. Accessing IDP Learning Instance

  - Scroll down the left navigation panel of AIRA.
  - Click on the "IDP" section. Upon clicking the IDP,  the Learning Instance window will open.
  - Utilise the search bar at the top right corner to quickly locate and access previous instances within AIRA.

### 2. Create New Learning Instance

  - To create a new instance, locate and click the "Add New Instance" button in the learning Instance window.
  - In the "Learning Instance Name" section, assign a unique and name to your instance.
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



