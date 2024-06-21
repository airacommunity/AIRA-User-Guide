<h1><span style="color: #411d66;">Overview                                                    <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e">
</span></h1>

<hr />

Triggers within AIRA workflow provide a means to apply specific business logic based on defined conditions or events. They enhance workflow customization and automation, ensuring precise actions are taken as per requirements.
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h3 id="creating-universal-triggers-using-the-app-section-in-aira-workflow" class="toc-header">Creating Universal Triggers Using the App Section in AIRA Workflow</h3>
<ul>
 	<li>Open the AIRA workflow platform.</li>
 	<li>Navigate to the module section located in the bottom-left corner of the screen.</li>
 	<li>Within the module section, click on "Apps" to access a list of available applications.</li>
 	<li>Scroll through the list of apps until you find "Trigger". Click on it to select it.</li>
 	<li>Once selected, a JavaScript option should appear. Drag and drop the JavaScript trigger into the workflow designer.</li>
 	<li>Double-click on the trigger block that you've dragged into the workflow canvas. This action should open a JavaScript code window.</li>
 	<li>Write your trigger logic using JavaScript. You may utilise predefined trigger functions to simplify your code. To know about the special trigger function, visit AIRA <a class="is-external-link" href="https://wiki.aira.fr/docs/trigger-functions/">Trigger Functions</a>.</li>
 	<li>After completing the trigger code, click on the "Submit" button located below the JavaScript code window.</li>
 	<li>Place the created trigger within the workflow according to your desired placement.</li>
 	<li>Connect the trigger block to other workflow components as needed.</li>
</ul>
<strong>Additional Options:</strong>

Right-click on the "Trigger Activity" app in the AIRA Designer workflow to access additional options:
<ul>
 	<li><strong>Unlink</strong>: Disconnect the app from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting</strong>: Access and modify the settings of the "trigger" app.</li>
 	<li><strong>Rename</strong>: Change the name of the apps for better organization.</li>
 	<li><strong>Trigger</strong>: Set triggers on the trigger app to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete</strong> <strong>Module</strong>: Permanently delete the trigger app from the workflow if it's no longer needed.</li>
</ul>
<h3 id="app-specific-trigger-setup-within-aira-workflow" class="toc-header">App-Specific Trigger Setup within AIRA Workflow</h3>
Suppose you're using the form function to collect data, including first name, last name, and age. Additionally, you're utilising the sheet app to store this collected information. However, there's a condition:

you only want to transfer data into the sheet if the first name provided in the form is "AJAY". To implement this condition, you need to apply a trigger.

<strong>Creating a Trigger:</strong>

<strong>1. Accessing Trigger Options:</strong>
<ul>
 	<li>Right-click on the sheet app to reveal trigger options.</li>
</ul>
<strong>2. Adding a Trigger</strong>:
<ul>
 	<li>Click on the trigger option to open a new window.</li>
 	<li>Locate the "Add Trigger" button positioned at the top-right corner of the window.</li>
</ul>
<strong>3. Creating a New Trigger:</strong>
<ul>
 	<li>Click on the "Add Trigger" button.</li>
 	<li>If no triggers are present, an empty list will be displayed.</li>
 	<li>Click on the plus sign above the trigger list to initiate the creation of a new trigger.</li>
</ul>
<strong>4. Providing Trigger Details:</strong>
<ul>
 	<li>Fill in the required information:
<ul>
 	<li>Title: Provide a title for the trigger.</li>
 	<li>Description: Optionally, add a description for clarity.</li>
 	<li>Script Type: Choose "JavaScript" as the script type.</li>
</ul>
</li>
</ul>
<strong>5. Scripting Logic:</strong>
<ul>
 	<li>Compose a JavaScript function to define the logic based on the specified condition (e.g., checking if the first name is "AJAY").</li>
 	<li>This JavaScript function encapsulates the business logic required for the trigger.</li>
 	<li>To know about the special trigger function, visit AIRA trigger functions.</li>
</ul>
<strong>6. Saving the Trigger:</strong>
<ul>
 	<li>After composing the JavaScript function, click on the submit button to save the trigger.</li>
</ul>
<strong>7. Configuring Trigger Placement:</strong>
<ul>
 	<li>Once the trigger is created, select it.</li>
 	<li>Decide whether the trigger should be applied before or after the app operation.</li>
 	<li>Drag and drop the trigger accordingly into the "before" or "after" trigger area to specify its placement.</li>
</ul>
<strong>Note :</strong> In our case we are creating a trigger in the sheet app so that we have to apply before the app. If we are creating a trigger on the form app we can call after the form app.

&nbsp;

---
![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
