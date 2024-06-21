<h1><span style="color: #411d66;">Overview                                                      <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e">
</span></h1>


The AIRA Form offers a user-friendly interface for manual data input in workflows, initiating case creation in the dedicated Case section. Cases allow structured data entry, with form elements as global variables usable across apps. After data entry, AIRA smoothly executes subsequent workflow steps, ensuring efficiency.
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h2 id="to-use-aira-forms-effectively-follow-these-steps" class="toc-header">To use AIRA Forms effectively, follow these steps:</h2>
<h3 id="navigate-to-aira-forms" class="toc-header">Navigate to AIRA Forms:</h3>
<ul>
 	<li>Go to the AIRA app section and locate the AIRA Forms option.</li>
 	<li>Click on it to access the forms functionality.</li>
</ul>
<h3 id="drag-and-drop-the-form" class="toc-header">Drag and Drop the Form:</h3>
<ul>
 	<li>Once in the AIRA Forms section, you'll see the option to create or select a form.</li>
 	<li>Simply drag and drop the AIRA Form component to the desired location where you want to integrate it into your workflow.</li>
</ul>
<h3 id="configure-the-form" class="toc-header">Configure the Form:</h3>
<ul>
 	<li>Double-click on the form to configure it.</li>
 	<li>This action will open a form configuration window.</li>
</ul>
<h3 id="select-existing-form" class="toc-header">Select Existing Form:</h3>
<ul>
 	<li>Choose the form you've previously created from the "Select Form" dropdown menu.</li>
 	<li>Define conditions for the execution of the form according to your workflow requirements. These conditions could determine when the form should be triggered or executed.Variable Selection
<ul>
 	<li>Begin by typing "$$" to initiate the variable list display.</li>
 	<li>Review the list of available variables and select the one relevant to your condition.</li>
</ul>
<strong>Operator Selection</strong>
<ul>
 	<li>After selecting the variable, choose the appropriate operator for your condition.</li>
 	<li>Operators include "=", "&gt;", "&lt;", and more, depending on your specific requirement.</li>
</ul>
<strong>Value Input</strong>
<ul>
 	<li>Enter the value against which you want to evaluate the condition.</li>
 	<li>This value will be compared to the variable using the selected operator to determine the condition's outcome.</li>
</ul>
<div class="code-toolbar">
<pre class="prismjs line-numbers language-js"><code class="language- language-js">For Example : $$time$$ === "12"</code></pre>
</div></li>
 	<li>Once conditions are applied, you have the option to either save or delete the form. If you're satisfied with the form and its conditions, proceed to save it for future workflow use.</li>
 	<li>After setting conditions and confirming your choices, click on the "Submit" button to save the form. This action ensures that the form is ready for use within your workflow.</li>
</ul>
<h3 id="create-new-form" class="toc-header">Create New Form</h3>
<ul>
 	<li>Click on the "Add new form" option at the top of the form configuration window.</li>
 	<li>A new window will open where you can provide a title and description for the form.</li>
 	<li>Click on the "Create form" button to proceed to the form creation window.</li>
 	<li>In the form creation window, you'll find various input components and custom options to design and customise your form according to your specific needs.</li>
</ul>
<h3 id="form-components-and-usage" class="toc-header">Form Components and Usage</h3>
<strong>Access Form Components:</strong>

On the left-hand side of the interface, you'll find a toolbox containing various form components.

<strong>Select the Form Component:</strong>

Locate the Form component in the toolbox.

<strong>Drag and Drop:</strong>

Drag the Form component from the toolbox to the desired location on the form designer.

<strong>Configure Settings:</strong>
<ul>
 	<li>Once you drop the Form component onto the form designer, a settings window will appear.</li>
 	<li>This window allows you to set parameters for the Form component according to your requirements.</li>
</ul>
<strong>Adjust Parameters:</strong>
<ul>
 	<li>Inside the component settings, you can adjust various parameters.</li>
 	<li>Tooltips are provided in front of the setting options to assist you in understanding their functionalities.</li>
</ul>
<h3 id="form-components-list" class="toc-header">Form Components List</h3>
<strong>Basic Inputs:</strong>
<ul>
 	<li><strong>Nested Form:</strong> Used to include multiple forms within a single form structure.</li>
 	<li><strong>Dropdown:</strong> Presents a list of options for selection in a dropdown menu.</li>
 	<li><strong>Hidden:</strong> A field that is part of the form but hidden from view.</li>
 	<li><strong>Text Field:</strong> Allows users to input single-line text data.</li>
 	<li><strong>Text Area:</strong> Allows users to input multiple lines of text.</li>
 	<li><strong>Data Grid:</strong> Presents data in a tabular format for input or display.</li>
 	<li><strong>Number:</strong> Accepts numeric input from users.</li>
 	<li><strong>Password:</strong> Conceals user input for sensitive data.</li>
 	<li><strong>Checkbox:</strong> Provides options for users to select one or multiple choices.</li>
 	<li><strong>Select Box:</strong> Similar to a dropdown, allows selection from a list of options.</li>
 	<li><strong>Select:</strong> Another form of selection input, often used for choosing from a list of options.</li>
 	<li><strong>Radio:</strong> Presents options as radio buttons for single selection.</li>
 	<li><strong>File:</strong> Allows users to upload files.</li>
 	<li><strong>Button:</strong> Triggers specific actions when clicked, such as form submission.</li>
</ul>
<strong>Advance:</strong>
<ul>
 	<li><strong>Email:</strong> Accepts input in the format of an email address.</li>
 	<li><strong>URL:</strong> Accepts input in the format of a URL.</li>
 	<li><strong>Phone Number:</strong> Accepts input in the format of a phone number.</li>
 	<li><strong>Day:</strong> Allows users to select a specific date.</li>
 	<li><strong>Time:</strong> Allows users to select a specific time.</li>
 	<li><strong>Currency:</strong> Accepts input in the format of a currency.</li>
 	<li><strong>Signature:</strong> Allows users to provide a digital signature.</li>
</ul>
<strong>Layout Components:</strong>
<ul>
 	<li><strong>Grid:</strong> Organises form elements in a grid layout for better alignment.</li>
 	<li><strong>Tab:</strong> Divides the form into tabs for organising and presenting information.</li>
 	<li><strong>HTML Components:</strong> Allows the inclusion of custom HTML elements within the form.</li>
 	<li><strong>Panel:</strong> Groups related form elements together within a panel for organisation.</li>
</ul>
<strong>Custom:</strong>
<ul>
 	<li><strong>Data Picker:</strong> Allows users to select a specific date or time from a calendar.</li>
 	<li><strong>Geo Location:</strong> Captures geographical location data.</li>
 	<li><strong>QR Scanner:</strong> Enables scanning of QR codes to input data or trigger actions.</li>
</ul>
<h3 id="addition-settings" class="toc-header">Addition Settings</h3>
In the additional settings located at the top right corner of the form designer, you'll find the following options:
<ol>
 	<li><strong>Preview:</strong> Allows you to preview the form layout and functionality before saving or deploying it. This feature helps ensure that the form appears and behaves as intended.</li>
 	<li><strong>JavaScript:</strong> Enables you to apply special form functions using JavaScript. You can write custom JavaScript code to enhance the form's functionality or implement specific behaviours based on user interactions. To Know more about it, visit <a class="is-external-link" href="https://wiki.aira.fr/docs/form-functions/">AIRA form functions</a>.</li>
 	<li><strong>Save:</strong> Saves the changes made to the form configuration. Clicking this option ensures that any modifications or updates to the form are retained.</li>
 	<li><strong>Import:</strong> Allows you to Import files or data to the form. This feature is useful for adding attachments or importing data into the form from external sources.</li>
 	<li><strong>Export:</strong> Enables you to Export files or data from the form. You can use this option to export form submissions, attachments, or any other relevant data for further analysis or storage.</li>
</ol>
These additional settings provide essential functionalities to manage and customise your form effectively, ensuring a seamless user experience and facilitating data collection and processing.

<strong>Additional Options:</strong>

Right-click on the app in the AIRA Designer workflow to access additional options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the app from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the app.</li>
 	<li><strong>Rename:</strong> Change the name of the apps for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the app to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the app from the workflow if it's no longer needed.</li>
 	<li><strong>Title :</strong> In the context you've provided, the title is a field or attribute used to assign a name or label to a form.</li>
 	<li><strong>Assignment Rule :</strong> An assignment rule, as described, is a mechanism used in case management systems to determine how tasks or cases are assigned to individuals or groups within an organisation. There are several types of assignment rules:
<ul>
 	<li><strong>Value-based Assignment:</strong> This type of rule assigns cases based on certain predefined variables or criteria.</li>
 	<li><strong>Self-service Assignment:</strong> cases are assigned to a designated group where members of that group can select and claim tasks themselves.</li>
 	<li><strong>Manual Assignment:</strong> This rule allows for manual assignment of cases by an administrator or supervisor. This could involve selecting a specific individual or team to handle a particular task or case.</li>
 	<li><strong>Report to Assignment:</strong> cases are assigned to the supervisor or manager of a particular individual. This can be useful for hierarchical structures where tasks need to be escalated to higher levels of authority.</li>
</ul>
</li>
</ul>
&nbsp;

----
![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
