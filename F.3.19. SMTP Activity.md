<h1><span style="color: #411d66;">Overview                                                    <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e">
</span></h1>

<hr />

SMTP, or Simple Mail Transfer Protocol, is a standard protocol used for sending email messages between servers. It allows email systems to communicate and transfer messages over the internet.

In the context of AIRA workflow, SMTP is used to send emails as part of automated processes. AIRA integrates SMTP functionality into its workflow system, allowing users to incorporate email notifications, alerts, or other communication mechanisms seamlessly into their automated workflows.

By configuring SMTP settings within AIRA workflow, users can set up triggers or actions that send email notifications to designated recipients based on specific events or conditions. This capability enhances workflow automation by enabling real-time communication and notifications, facilitating smoother collaboration and information dissemination within organisations.
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h2 id="using-smtp-in-aira-workflow" class="toc-header">Using SMTP in AIRA Workflow:</h2>
<h3 id="accessing-smtp-in-aira-job" class="toc-header">Accessing SMTP in AIRA Job:</h3>
<ul>
 	<li>Navigate to the APP section within the AIRA job interface.</li>
 	<li>Search for "SMTP" and click on the SMTP option that appears.</li>
</ul>
<h3 id="adding-send-email-app-to-workflow" class="toc-header">Adding Send Email App to Workflow:</h3>
<ul>
 	<li>Once SMTP is selected, the option to send emails will appear.</li>
 	<li>Simply drag and drop the "Send Email" app from the SMTP options into the AIRA workflow designer.</li>
</ul>
<h3 id="positioning-the-send-email-app" class="toc-header">Positioning the Send Email App:</h3>
<ul>
 	<li>Connect the "Send Email" app in the desired position within the AIRA workflow canvas.</li>
</ul>
<h3 id="configuring-the-send-email-app" class="toc-header">Configuring the Send Email App:</h3>
<ul>
 	<li>Double-click on the "Send Email" app to open the configuration window</li>
</ul>
<h3 id="selecting-connection" class="toc-header">Selecting Connection:</h3>
<ul>
 	<li>Choose the connection previously created from the connection section. This connection will be used to send emails.</li>
 	<li>If a connection is not created before, click on the add button to create a connection. To know more about connections visit <a class="is-external-link" href="https://wiki.aira.fr/docs/connections/">AIRA Connection</a> section.</li>
</ul>
<h3 id="defining-recipient-type" class="toc-header">Defining Recipient Type:</h3>
<ul>
 	<li>Choose the recipient type from the options: VALUE, VARIABLE, USER, GROUP.
<ul>
 	<li><strong>VALUE</strong>: Input the recipient's email address directly into the Recipient section.</li>
 	<li><strong>VARIABLE</strong>: Select a variable from the Recipient section that stores the recipient's email address.</li>
 	<li><strong>USER</strong>: Choose users from AIRA in the Recipient section.</li>
 	<li><strong>GROUP</strong>: Select group users from AIRA in the Recipient section.</li>
</ul>
</li>
</ul>
<h3 id="cc-carbon-copy" class="toc-header">CC (Carbon Copy):</h3>
<ul>
 	<li>Use the Variable option to include CC email addresses stored in a variable, or manually enter CC email addresses.</li>
</ul>
<h3 id="subject" class="toc-header">Subject:</h3>
<ul>
 	<li>Similar to CC, use the Variable option to insert the subject of the email from a variable, or manually enter the subject.</li>
</ul>
<h3 id="selecting-email-template" class="toc-header">Selecting Email Template:</h3>
<ul>
 	<li>Choose a pre-developed email template from the available options.</li>
 	<li>If no suitable template is available, click on the plus sign above the template section to create a new template.</li>
</ul>
<h3 id="creating-a-new-email-template" class="toc-header">Creating a New Email Template:</h3>
<ul>
 	<li>Click on the plus sign to initiate template creation.</li>
 	<li>Provide a name for the template.</li>
 	<li>Use the template creation section below to design the content of the email.</li>
 	<li>After completing the template, click on the create template button to save it.</li>
</ul>
<h3 id="selecting-attachments" class="toc-header">Selecting Attachments:</h3>
<ul>
 	<li>Beneath the template selection, locate the File section.</li>
 	<li>Choose a variable containing the file to be attached, or upload a file from your local system by clicking the upload button above the file section.</li>
</ul>
<h3 id="finalising-configuration" class="toc-header">Finalising Configuration:</h3>
<ul>
 	<li>Once all settings have been configured according to your requirements, review them to ensure accuracy.</li>
 	<li>Click the submit button located below the configuration window to save the settings for sending the email.</li>
</ul>
<strong>Additional Options:</strong>

Right-click on the "Trigger Activity" app in the AIRA Designer workflow to access additional options:
<ul>
 	<li><strong>Unlink</strong>: Disconnect the app from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting</strong>: Access and modify the settings of the app.</li>
 	<li><strong>Rename</strong>: Change the name of the apps for better organization.</li>
 	<li><strong>Trigger</strong>: Set triggers on the app to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete</strong> <strong>Module</strong>: Permanently delete the app from the workflow if it's no longer needed.</li>
</ul>
&nbsp;

-----
![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
