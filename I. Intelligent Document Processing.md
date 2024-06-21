<h1><span style="color: #411d66;">Overview                                                     <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e">
</span></h1>


Welcome to the AIRA Intelligent Document Processing (IDP) User Guide! This section will walk you through the steps of using the IDP function within AIRA, providing you with a seamless and efficient experience in handling document-related tasks. To know how to use IDP in AIRA Workflow visit AIRA IDP App.

The Intelligent Document Processing (IDP) module within the workflow plays a pivotal role in automating processes that involve extracting data from files. IDP is specifically designed to efficiently extract relevant information from documents, facilitating a streamlined and automated workflow. By incorporating the IDP module, users can harness the power of automation to accurately and swiftly process data from files, enhancing the overall efficiency of their business processes. This module serves as a crucial component in automating document-centric tasks, reducing manual efforts, and ensuring accuracy in data extraction processes.
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h2 id="steps-to-create-learning-instance" class="toc-header">Steps To Create Learning Instance</h2>
<h3 id="h-1-accessing-idp-learning-instance" class="toc-header">1. Accessing IDP Learning Instance</h3>
<ul>
 	<li>Scroll down the left navigation panel of AIRA.</li>
 	<li>Click on the "IDP" section. Upon clicking the IDP, the Learning Instance window will open.</li>
 	<li>Utilise the search bar at the top right corner to quickly locate and access previous instances within AIRA.</li>
</ul>
<h3 id="h-2-create-new-learning-instance" class="toc-header">2. Create New Learning Instance</h3>
<ul>
 	<li>To create a new instance, locate and click the "Add New Instance" button in the learning Instance window.</li>
 	<li>In the "Learning Instance Name" section, assign a unique name to your instance.</li>
 	<li>Find the "Drop File" section below the "Learning Instance Name." Upload files into this section by dragging and dropping or browsing. Supported file formats include JPG, JPEG, PNG, and PDF.</li>
 	<li>Click on "Create" to initiate the instance creation process.</li>
</ul>
<h3 id="h-3-select-document-type" class="toc-header">3. Select Document Type</h3>
<ul>
 	<li>Locate the dropdown button situated next to deploy button.</li>
 	<li>Click on the dropdown button to reveal a list of document formats, such as "Form," "Invoice," and others.</li>
 	<li>Choose the appropriate document type from the available options.</li>
</ul>
<h3 id="h-4-extract-document-data" class="toc-header">4. Extract Document Data</h3>
<ul>
 	<li>Choose the "Extract Data" button to extract information from the documents.</li>
 	<li>This action triggers the extraction process, capturing all available textual data within the documents.</li>
 	<li>Add Custom Rule if data is not extracted or errors occur during the data extraction of any field.</li>
</ul>
<h4 id="add-new-field" class="toc-header">Add New Field</h4>
<ul>
 	<li>If any field is not automatically extracted, navigate to the "Field" section.</li>
 	<li>Within the Field section, you'll find two options: Field Labels and Field Name.</li>
 	<li>Fill in the "Field Labels" section with the desired name for the selected field.</li>
 	<li>In the "Field Name" section, specify the actual field name you are looking for.</li>
 	<li>Click on the "Add" button to apply the new fields.</li>
 	<li>Finally, click on the "Extract Data" button to extract all the fields.</li>
 	<li>Add Custom Rule if data is not extracted properly.</li>
</ul>
<h4 id="add-custom-rule" class="toc-header">Add Custom Rule</h4>
In the event that some data is not extracted or errors occur during the data extraction of any field, AIRA provides the option to add custom rules for more precise extraction. Here's how to utilise the "Add Custom Rule" option:
<ul>
 	<li>Identify the field where extraction errors or omissions have occurred.</li>
 	<li>Navigate to the bottom right side of the field and click on the "Add Custom Rule" option.</li>
 	<li>A new window will pop up, displaying the OCR-processed text for the selected field.</li>
 	<li>Below the OCR text, a "Custom Rule Bar" is available for setting exact data rules.</li>
 	<li>In the Custom Rule Bar, the first section is for filling in the "Search Item." Identify the item that helps locate the field that you want to extract.</li>
 	<li>The next section allows you to set the logic for the custom rule. Define the logic based on the specific issue. List of logic is given below :
<ul>
 	<li>Find Text In Next Line</li>
 	<li>Find Next Text On Same Line</li>
 	<li>Find Previous Text On Same Line</li>
 	<li>Find Next Word On Same Line</li>
 	<li>Start With Keyword</li>
 	<li>Contain Keyword</li>
 	<li>Next N Line</li>
 	<li>Previous N Line</li>
 	<li>Next Specific Line</li>
 	<li>Find Previous Specific Line</li>
 	<li>Find Specific Words Start to End</li>
</ul>
</li>
 	<li>Click on the "Apply Rule" button to apply the custom rule to the selected field.</li>
 	<li>If needed, additional rules can be added by clicking the "Add Rule" button.</li>
 	<li>Rules can be deleted by clicking the "Delete" button.</li>
</ul>
<blockquote class="is-warning">The issue is related to the "Customer Name" field, and the Bill Number is just above the “Customer Name,” so the search item is Bill Number. According to our example, the logic for the custom rule is Find Text in the Next Line.</blockquote>
<h3 id="h-5-extract-table" class="toc-header">5. Extract Table</h3>
<ul>
 	<li>Beneath the "Extract Data" section, locate the "Extract Table" section.</li>
 	<li>Click on the "Extract Table" button within the Table Extraction section.</li>
 	<li>A new window will appear, displaying the extracted table on the right side.</li>
 	<li>Navigate to the right section of the window and click on the table of interest.</li>
 	<li>The data of the selected table will be displayed in the lower part of the window.</li>
 	<li>To download the desired table, click on the download button next to the "Confirm Table" button.</li>
 	<li>Once you've selected the table, confirm your choice by clicking the "Confirm Table" button.</li>
</ul>
<h3 id="h-6-additional-setting" class="toc-header">6. Additional Setting</h3>
Click on the setting button located at the top right side of the window. It helps to create the document image.There are three options available in the settings :
<ul>
 	<li>Grey Scale: When toggled on, it converts the document color to grayscale.</li>
 	<li>Binarization: Converts the grayscale document into black and white. It requires two parameters:
<ul>
 	<li>Max: Its limit is 255. If we select a maximum value (e.g., 180), grayscale values above this threshold convert into white.</li>
 	<li>Threshold: Its limit is 255. If we select a threshold value (e.g., 180), grayscale values lower than this threshold convert into black.</li>
</ul>
</li>
 	<li>Noise Deduction: When toggled on, it enhances the picture quality by reducing noise.</li>
 	<li>After applying all the required setting click on the apply button to save and execute.</li>
</ul>
<h3 id="h-7-deploying-the-learning-instance" class="toc-header">7. Deploying the Learning Instance</h3>
<ul>
 	<li>Confirm that all data extraction processes have been executed accurately.</li>
 	<li>Review the extracted information to ensure completeness and correctness.</li>
 	<li>Navigate to the top right corner of the window.</li>
 	<li>Click on the "Deploy Instance" button.</li>
 	<li>Upon clicking, the learning instance is deployed, making it available for use within the AIRA workflow.</li>
 	<li>The instance is now ready to contribute to the automation and efficiency of your document processing tasks.</li>
</ul>
<h3 id="conclusion" class="toc-header">Conclusion</h3>
As we conclude this section, envision the powerful fusion of Intelligent Document Processing with AIRA. The insights gained here pave the way for transforming document-related challenges into opportunities, unlocking new dimensions of efficiency and automation within your workflows.

&nbsp;

----
![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
