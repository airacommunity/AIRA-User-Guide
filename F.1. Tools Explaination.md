![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# Tools Explaination  <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">


## Overview

The Tools Section is the powerhouse of capabilities designed to elevate your workflow by providing robust logic-building tools. It serves as your go-to destination for infusing intelligence and logic into your workflows, empowering users to define the flow and decision points to ensure a customised and efficient process.

## Exploring Logical Tools in AIRA


> - Decision Making : Under development
> - Do While : Pending - Take Clearity From Developement Team
> - Do While End : Under Developement
> - For Join : Pending - Take Clearity From Developement Team
> - Join : Pending - Take Clearity From Developement Team

### Set Variable
The Set Variable tool is a component utilized within workflow design environments to establish and define input variables. By incorporating the Set Variable tool into a workflow and establishing connections with other tools or applications, these downstream elements gain access to the variable generated by the Set Variable tool.

#### How to Use the Set Variable Tool:

- **Drag and Drop:**
   - Locate the "Set Variable" tool in the Tools Section of the AIRA Designer interface.
   - Drag the "Set Variable" tool onto your workflow canvas.

- **Connect:**
   - Connect the "Set Variable" tool to the app or tool where you want to apply the variable.
   - This can be done by dragging a connection line from the output of the preceding action to the input of the "Set Variable" tool.

- **Configure:**
   - Double-click on the "Set Variable" tool to open its settings.
   - In the settings, you will find the Input field.
   - Define the Input: Input the information you want to assign to the variable.
   - This could be a specific value, a result from a previous action, or another variable.
   - You can directly enter the value or select a variable from elsewhere in the workflow.
   - Click on the "Submit" button to save the settings.

- **Additional Options:**

  Right-click on the "Set Variable" tool in the AIRA Designer workflow to access additional options:
  
   - **Unlink:** Disconnect the "Set Variable" tool from any connected apps or tools in the workflow.
   - **Setting:** Access and modify the settings of the "Set Variable" tool.
   - **Rename:** Change the name of the "Set Variable" tool for better organization.
   - **Trigger:** Set triggers on the "Set Variable" tool to initiate actions based on specified conditions or events.
   - **Delete Module:** Permanently delete the "Set Variable" tool from the workflow if it's no longer needed.

### Subworkflow
The "Sub Workflow" tool in AIRA Designer allows users to incorporate other workflows within their current workflow, promoting modularity and reusability.

#### How to Use the Sub Workflow Tool:

- **Drag and Drop:**
   - Locate the "Sub Workflow" tool in the Tools Section of the AIRA Designer interface.
   - Drag the "Sub Workflow" tool onto your workflow canvas.

- **Connect:**
   - Connect the "Sub Workflow" tool to the required place in your workflow where you want to invoke the subworkflow.
   - Drag connection lines from the output of the preceding action to the input of the "Sub Workflow" tool.

- **Configure Subworkflow:**
   - Double-click on the "Sub Workflow" tool to configure its settings.
   - Choose the job or workflow that you want to use within your current workflow.
   - Provide input parameters for the sub workflow by specifying keys and their corresponding values.
   - Optionally, choose variables instead of fixed values for the input parameters.
   - Click on the "Submit" button to save the settings.

- **Additional Options:**

  Right-click on the "Subworkflow" tool in the AIRA Designer workflow to encounter five available options:

   - **Unlink:** Disconnect the "Sub Workflow" tool from any connected apps or tools in the workflow.
   - **Setting:** Access and modify the settings of the "Sub Workflow" tool.
   - **Rename:** Change the name of the "Sub Workflow" tool for better organization.
   - **Trigger:** Set triggers on the "Sub Workflow" tool to initiate actions based on specified conditions or events.
   - **Delete Module:** Permanently delete the "Sub Workflow" tool from the workflow if it's no longer needed.

### Switch
The "Switch" tool in AIRA Designer allows users to implement conditional branching within their workflow, directing the flow of actions based on specified conditions.

#### How to Use the Switch Tool:

- **Drag and Drop:**
   - Find the "Switch" tool in the Tools Section of the AIRA Designer interface.
   - Drag the "Switch" tool onto your workflow canvas.

- **Connect:**
   - Connect the "Switch" tool to the required place in your workflow where you want to implement conditional branching.
   - This can be done by dragging connection lines from the output of the preceding action to the input of the "Switch" tool and connect output of the switch tool with the multiple apps which you want to switch according to conditions.

- **Open Switch Configuration:**
   - Locate the "Switch" tool in your workflow.
   - Double-click on the "Switch" tool to access its configuration settings.

- **Define Logic Expression:**

   - Within the configuration window, locate the expression field for defining the logic of the switch process.
   - Construct an expression that encapsulates the conditions and actions for directing the workflow.
   - Utilize operators such as greater than (>), less than (<), equal to (=), etc., within the expression.
   - Incorporate variables within the expression to enable dynamic evaluation.
   - ``` For example: $$workflow.variables.result.age$$ >= 12 ```
- **Ensure Accuracy:**
   - Review the expression to ensure it accurately captures the intended logic for directing the workflow.
   - Verify that all conditions and corresponding actions are appropriately defined.

- **Set Branching Conditions:**
   - After defining the expression, proceed to set the operator and conditions for branching applications or tools.
   - Optionally, apply logical operators such as AND and OR to combine multiple branching conditions.

- **Submit Configuration:**
   - Once satisfied with the configuration, click on the "Submit" button to save the settings.

- **Additional Options:**

  Right-click on the "Switch" tool in the AIRA Designer workflow to encounter five available options:

   - **Unlink:** Disconnect the "Swtich" tool from any connected apps or tools in the workflow.
   - **Setting:** Access and modify the settings of the "Switch" tool.
   - **Rename:** Change the name of the "Switch" tool for better organization.
   - **Trigger:** Set triggers on the "Switch" tool to initiate actions based on specified conditions or events.
   - **Delete Module:** Permanently delete the "Switch" tool from the workflow if it's no longer needed.


### Terminate
Terminate refers to a tool used to abruptly stop a process or task before it finishes naturally. This tool is handy when there's a need to halt an operation due to an error, a specific condition, or as part of the planned workflow logic. By activating "Terminate," the ongoing task immediately ceases, preventing any further actions from taking place. This feature offers control and flexibility, enabling users to manage workflow flow according to specific needs and circumstances.

#### How to Use the Terminate Tool

- **Drag and Drop:**
   - Find the "Terminate" tool in the Tools Section of the AIRA Designer interface.
   - Drag the "Terminate" tool onto your workflow canvas.

- **Connect:**
   - Connect the "Terminate" tool to the app or tool where you want to apply the termination.
   - This can be done by dragging a connection line from the output of the preceding action to the input of the "Terminate" tool.

- **Configure:**
   - Double-click on the "Terminate" tool to open its settings.
   - Set the Status: Choose between "Completed" or "Failed" to indicate the status of the terminated process.
   - Define the Output: Specify what output or result should be provided after the termination of the process.
   - Provide a Termination Reason: Describe the reason for the termination.
   - Click on the "Submit" button to save the settings.

- **Additional Options:**

  Right-click on the "Terminate" tool in the AIRA Designer workflow to encounter five available options:

   - **Unlink:** Disconnect the "Terminate" tool from any connected apps or tools in the workflow.
   - **Setting:** Access and modify the settings of the "Terminate" tool.
   - **Rename:** Change the name of the "Terminate" tool for better organization.
   - **Trigger:** Set triggers on the "Terminate" tool to initiate actions based on specified conditions or events.
   - **Delete Module:** Permanently delete the "Terminate" tool from the workflow if it's no longer needed.

### WAIT
The "Wait" tool enables users to specify a duration of time for the workflow to pause before proceeding to the next step. This pause can be based on either a specific date and time or a relative time period, such as waiting for a certain number of minutes, hours, or days.

#### How to Use the "Wait" Tool

- **Drag and Drop:**
   - Go to the Tools Section of the AIRA Designer interface.
   - Find the "Wait" tool and drag it onto the workflow canvas.

- **Connect:**
   - Drag a connection line from the output of the preceding action to the input of the "Wait" tool.
   - Then, drag a connection line from the output of the "Wait" tool to the input of the subsequent action.

- **WAIT FOR - Configure:**
   - **Select the Tool:** Double-click on the "Wait" tool to open its settings.
   - **Choose WAIT-FOR:**
       - Select the "WAIT-FOR" option from the settings menu.
   - **Fill Details:**
       - Enter the desired number of days, hours, and minutes to wait before proceeding.
       - For example, if you want to wait for 1 day, 2 hours, and 30 minutes, enter these values in their respective fields.
   - **Submit:**
       - Click on the "Submit" button to save the settings.

- **WAIT-SPECIFIED-DATE-TIME - Configure:**
   - **Select the Tool:** Double-click on the "Wait" tool to open its settings.
   - **Choose WAIT-SPECIFIED-DATE-TIME:**
       - Select the "WAIT-SPECIFIED-DATE-TIME" option from the settings menu.
   - **Enter Date and Time:**
       - Enter the specific date and time you want to wait until before proceeding.
       - Ensure the format is correct, including the date, time, and time zone if applicable.

- **Submit:**
    - Click on the "Submit" button to save the settings.

- **Additional Options:**

  When right-clicking on the "Wait" tool in the AIRA Designer workflow, you'll encounter five available options:

   - **Unlink:** Disconnect the "Wait" tool from any connected apps or tools in the workflow.
   - **Setting:** Access and modify the settings of the "Wait" tool.
   - **Rename:** Change the name of the "Wait" tool for better organization.
   - **Trigger:** Set triggers on the "Wait" tool to initiate actions based on specified conditions or events.
   - **Delete Module:** Permanently delete the "Wait" tool from the workflow if it's no longer needed.





----

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-caution.jpg?raw=true"> Kindly note that the content provided is currently in development and is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

----

<table border="0" align="center">
  <tr>
    <td><a href="https://aira.fr/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20web.png?raw=true" alt="Image 5" width="30" height="30"></a></td>
    <td><a href="https://www.linkedin.com/company/aira-rpa/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20linkedin.png?raw=true" alt="Image 1" width="30" height="30"></a></td>
    <td><a href="https://in.pinterest.com/connect_aira/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20pinterest.png?raw=true" alt="Image 2" width="30" height="30"></a></td>
    <td><a href="https://www.youtube.com/channel/UCHHCcwQrx-_19sAhu-2R4ww"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20youtube.png?raw=true" alt="Image 3" width="30" height="30"></a></td>
    <td><a href="https://twitter.com/Aira_RPA"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20twitter.png?raw=true" alt="Image 4" width="30" height="30"></a></td>
    <td><a href="mailto:connect@aira.fr"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20gmail.png?raw=true" alt="Image 6" width="30" height="30"></a></td>
  </tr>
</table>


![Footer](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/6bb25f04-ad9c-476c-b653-c3c1dac1a868)