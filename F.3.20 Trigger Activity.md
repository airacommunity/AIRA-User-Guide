![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# Trigger Activity <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">

## Overview
Triggers within AIRA workflow provide a means to apply specific business logic based on defined conditions or events. They enhance workflow customization and automation, ensuring precise actions are taken as per requirements.

<br>

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/Icon-Warning.png?raw=true"> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

<br>

### Creating Universal Triggers Using the App Section in AIRA Workflow

- Open the AIRA workflow platform.
- Navigate to the module section located in the bottom-left corner of the screen.
- Within the module section, click on "Apps" to access a list of available applications.
- Scroll through the list of apps until you find "Trigger". Click on it to select it.
- Once selected, a JavaScript option should appear. Drag and drop the JavaScript trigger into the workflow designer.
- Double-click on the trigger block that you've dragged into the workflow canvas. This action should open a JavaScript code window.
- Write your trigger logic using JavaScript. You may utilise predefined trigger functions to simplify your code. To know about the special trigger function, visit AIRA Trigger Functions. 
- After completing the trigger code, click on the "Submit" button located below the JavaScript code window.
- Place the created trigger within the workflow according to your desired placement.
- Connect the trigger block to other workflow components as needed.

**Additional Options:**

Right-click on the "Trigger Activity" app in the AIRA Designer workflow to access additional options:

- Unlink: Disconnect the app from any connected apps or tools in the workflow.
- Setting: Access and modify the settings of the "trigger" app.
- Rename: Change the name of the apps for better organization.
- Trigger: Set triggers on the trigger app to initiate actions based on specified conditions or events.
- Delete Module: Permanently delete the trigger app from the workflow if it's no longer needed.

### App-Specific Trigger Setup within AIRA Workflow

Suppose you're using the form function to collect data, including first name, last name, and age. Additionally, you're utilising the sheet app to store this collected information. However, there's a condition:

you only want to transfer data into the sheet if the first name provided in the form is "AJAY". To implement this condition, you need to apply a trigger.

**Creating a Trigger:**

**1. Accessing Trigger Options:**
- Right-click on the sheet app to reveal trigger options.

**2. Adding a Trigger**:
- Click on the trigger option to open a new window.
- Locate the "Add Trigger" button positioned at the top-right corner of the window.

**3. Creating a New Trigger:**
- Click on the "Add Trigger" button.
- If no triggers are present, an empty list will be displayed.
- Click on the plus sign above the trigger list to initiate the creation of a new trigger.

**4. Providing Trigger Details:**
- Fill in the required information:
    - Title: Provide a title for the trigger.
    - Description: Optionally, add a description for clarity.
    - Script Type: Choose "JavaScript" as the script type.

**5. Scripting Logic:**
- Compose a JavaScript function to define the logic based on the specified condition (e.g., checking if the first name is "AJAY").
- This JavaScript function encapsulates the business logic required for the trigger.
- To know about the special trigger function, visit AIRA trigger functions. 

**6. Saving the Trigger:**
- After composing the JavaScript function, click on the submit button to save the trigger.

**7. Configuring Trigger Placement:**
- Once the trigger is created, select it.
- Decide whether the trigger should be applied before or after the app operation.
- Drag and drop the trigger accordingly into the "before" or "after" trigger area to specify its placement.

**Note** : In our case we are creating a trigger in the sheet app so that we have to apply before the app. If we are creating a trigger on the form app we can call after the form app.

----

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


