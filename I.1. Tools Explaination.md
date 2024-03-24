![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# Tools Explaination  <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">


## Overview

The Tools Section is the powerhouse of capabilities designed to elevate your workflow by providing robust logic-building tools. It serves as your go-to destination for infusing intelligence and logic into your workflows, empowering users to define the flow and decision points to ensure a customised and efficient process.

## Exploring Logical Tools in AIRA

### WAIT

- **Locate the Tool**: 
   - Navigate to the Tools Section of the AIRA Designer interface.
   - Drag the "Wait" tool onto the workflow canvas.

- **Connect the Tool**: 
   - Connect the "Wait" tool between the two actions or steps where you want to introduce a delay.
   - Drag a connection line from the output of the preceding action to the input of the "Wait" tool, and then from the output of the "Wait" tool to the input of the subsequent action.

- **Open Settings**:
   - Double-click on the "Wait" tool to open its settings.

  - **WAIT-FOR Option**:
     - **Purpose**: Specify a relative time duration to wait before proceeding with the workflow.
     - **Steps**:
       - Select the Tool: Double-click on the "Wait" tool.
       - Choose WAIT-FOR: Select the "WAIT-FOR" option.
       - Fill Details:
         - Enter the desired number of days, hours, and minutes to wait.
         - Example: If waiting for 1 day, 2 hours, and 30 minutes, enter these values.
         - Submit: Click "Submit" to save settings.
  
  - **WAIT-SPECIFIED-DATE-TIME Option**:
     - **Purpose**: Specify an exact date and time to wait until before proceeding.
     - **Steps**:
       - Select the Tool: Double-click on the "Wait" tool.
       - Choose WAIT-SPECIFIED-DATE-TIME.
       - Enter Date and Time:
         - Enter the specific date and time.
         - Ensure correct format and time zone if applicable.
         - Submit: Click "Submit" to save settings.

#### Additional Options:

- **Unlink**:
  - **Purpose**: Disconnect the "Wait" tool from connected apps or tools.
  - **Usage**: Right-click on the "Wait" tool and select "Unlink" to remove connections.

- **Setting**:
  - **Purpose**: Access and modify the settings of the "Wait" tool.
  - **Usage**: Right-click on the "Wait" tool and select "Setting" to access configuration settings.

- **Rename**:
  - **Purpose**: Rename the "Wait" tool for organization and clarity.
  - **Usage**: Right-click on the "Wait" tool and select "Rename" to change its name.

- **Trigger**:
  - **Purpose**: Set triggers on the "Wait" tool to initiate actions based on specified conditions or events.
  - **Usage**: Right-click on the "Wait" tool and select "Trigger" to configure triggers.

- **Delete Module**:
  - **Purpose**: Permanently delete the "Wait" tool from the workflow.
  - **Usage**: Right-click on the "Wait" tool and select "Delete Module" to remove it.


### Terminate

The "Terminate" tool in the AIRA Designer workflow is used to abruptly end a process or task before its natural completion. Here's a step-by-step guide on how to use the "Terminate" tool:

### How to Use the Terminate Tool:

Drag and Drop: Find the "Terminate" tool in the Tools Section of the AIRA Designer interface. Drag the "Terminate" tool onto your workflow canvas.

  

Connect: Connect the "Terminate" tool to the app or tool where you want to apply the termination. This can be done by dragging a connection line from the output of the preceding action to the input of the "Terminate" tool.

  

Configure:

  


  

-   Double-click on the "Terminate" tool to open its settings.
    
-   Set the Status: Choose between "Completed" or "Failed" to indicate the status of the terminated process. This helps to clarify whether the process was successfully completed or not.
    
-   Define the Output: Specify what output or result should be provided after the termination of the process. This could be a specific value or a variable that you've defined elsewhere in the workflow.
    
-   Provide a Termination Reason: Describe the reason for the termination, which can help with debugging or understanding the workflow. This can be a fixed value or a variable.
    
-   Click on the "Submit" button to save the settings.
    

### Additional Options:

When you right-click on the "Terminate" tool in the AIRA Designer workflow, you will encounter five available options:

  


  

1. Unlink:

Purpose: This option allows you to disconnect the "Terminate" tool from any connected apps or tools in the workflow.

Usage: Right-click on the "Terminate" tool and select "Unlink" to remove its connections.

  

2. Setting:

Purpose: Similar to opening the configuration settings by double-clicking, this option provides another way to access and modify the settings of the "Terminate" tool.

Usage: Right-click on the "Terminate" tool and select "Setting" to access its configuration settings.

  

3. Rename:

Purpose: This option enables you to rename the "Terminate" tool, which can help with organisation and clarity within your workflow.

Usage: Right-click on the "Terminate" tool and select "Rename" to change its name.

  

4. Trigger:

Purpose: The "Trigger" option allows you to set triggers on the "Terminate" tool, enabling it to initiate actions based on specified conditions or events.

Usage: Right-click on the "Terminate" tool and select "Trigger" to configure triggers according to your workflow requirements.

  

5. Delete Module:

Purpose: If you no longer need the "Terminate" tool in your workflow, you can use this option to permanently delete it.

Usage: Right-click on the "Terminate" tool and select "Delete Module" to remove it from the workflow.

## Set Variable

The "Set Variable" tool in the AIRA Designer workflow is used to define and assign values to variables within the workflow. Here's a step-by-step guide on how to use the "Set Variable" tool:

### How to Use the Set Variable Tool:


  

Drag and Drop: Locate the "Set Variable" tool in the Tools Section of the AIRA Designer interface. Drag the "Set Variable" tool onto your workflow canvas.

  

Connect: Connect the "Set Variable" tool to the app or tool where you want to apply the variable. This can be done by dragging a connection line from the output of the preceding action to the input of the "Set Variable" tool.

  

Configure:

  

-   Double-click on the "Set Variable" tool to open its settings.
    
-   In the settings, you will find the Input field.
    
-   Define the Input: Here, you can input the information that you want to assign to the variable. This could be a specific value, a result from a previous action, or another variable. You can directly enter the value or select a variable that you have created elsewhere in the workflow.
    
-   Click on the "Submit" button to save the settings.
    

### Additional Options:

When you right-click on the "Set Variable" tool in the AIRA Designer workflow, you will encounter five available options:

  

1. Unlink:

Purpose: This option allows you to disconnect the "Set Variable" tool from any connected apps or tools in the workflow.

Usage: Right-click on the "Set Variable" tool and select "Unlink" to remove its connections.

  

2. Setting:

Purpose: Similar to opening the configuration settings by double-clicking, this option provides another way to access and modify the settings of the "Set Variable" tool.

Usage: Right-click on the "Set Variable" tool and select "Setting" to access its configuration settings.

  

3. Rename:

Purpose: This option enables you to rename the "Set Variable" tool, which can help with organisation and clarity within your workflow.

Usage: Right-click on the "Set Variable" tool and select "Rename" to change its name.

  

4. Trigger:

Purpose: The "Set Variable" option allows you to set triggers on the "Set Variable" tool, enabling it to initiate actions based on specified conditions or events.

Usage: Right-click on the "Set Variable" tool and select "Trigger" to configure triggers according to your workflow requirements.

  

5. Delete Module:

Purpose: If you no longer need the "Set Variable" tool in your workflow, you can use this option to permanently delete it.

Usage: Right-click on the "Set Variable" tool and select "Delete Module" to remove it from the workflow.

## DO WHILE

The "Do While" tool in the AIRA workflow designer is used to create loop structures within your workflow. Here's a step-by-step guide on how to use the "Do While" tool:

### How to Use the Do While Tool:


Drag and Drop: Locate the "Do While" tool in the Tools Section of the AIRA Designer interface. Drag the "Do While" tool onto your workflow canvas.

  

Connect: Connect the "Do While" tool to the required place in your workflow where you want the loop to begin and end. This can be done by dragging connection lines from the output of the preceding action to the input of the "Do While" tool, and then from the output of the "Do While" tool back to the input of the action where the loop should end.

  

Configure Loop Parameters:

  

-   Drag and drop the app or action that you want to include in the loop into the "Do While" tool. This action will be repeated as long as the specified condition is true.
    
-   Right-click on the "Do While" tool and select "SETTING" to set the loop parameters and condition.
    
-   In the settings, You can place any value in the parameters or choose variables that you have created elsewhere in the workflow.
    
-   Click on the "Submit" button to save the loop parameters and condition.
    

### Additional Options:

When you right-click on the "Do While" tool in the AIRA Designer workflow, you will encounter five available options:

  


  

1. Unlink:

Purpose: This option allows you to disconnect the "Do While" tool from any connected apps or tools in the workflow.

Usage: Right-click on the "Do While" tool and select "Unlink" to remove its connections.

  

2. Setting:

Purpose: Similar to opening the configuration settings by double-clicking, this option provides another way to access and modify the settings of the "Do While" tool.

Usage: Right-click on the "Do While" tool and select "Setting" to access its configuration settings.

  

3. Rename:

Purpose: This option enables you to rename the "Do While" tool, which can help with organisation and clarity within your workflow.

Usage: Right-click on the "Do While" tool and select "Rename" to change its name.

  

4. Trigger:

Purpose: The "Do While" option allows you to set triggers on the "Do While" tool, enabling it to initiate actions based on specified conditions or events.

Usage: Right-click on the "Do While" tool and select "Trigger" to configure triggers according to your workflow requirements.

  

5. Delete Module:

Purpose: If you no longer need the "Do While" tool in your workflow, you can use this option to permanently delete it.

Usage: Right-click on the "Do While" tool and select "Delete Module" to remove it from the workflow.

## Subworkflow

The "Sub Workflow" tool in AIRA Designer allows users to incorporate other workflows within their current workflow, promoting modularity and reusability. Here's a step-by-step guide on how to use the "Sub Workflow" tool:

### How to Use the Sub Workflow Tool:


Drag and Drop: Locate the "Sub Workflow" tool in the Tools Section of the AIRA Designer interface. Drag the "Sub Workflow" tool onto your workflow canvas.

  

Connect: Connect the "Sub Workflow" tool to the required place in your workflow where you want to invoke the subworkflow. This can be done by dragging connection lines from the output of the preceding action to the input of the "Sub Workflow" tool.

  

Configure Subworkflow:

  

-   Double-click on the "Sub Workflow" tool to configure its settings.
    
-   Choose the job or workflow that you want to use within your current workflow. This job should be predefined and available within your AIRA environment.
    
-   Provide input parameters for the sub workflow by specifying keys and their corresponding values. These parameters can be fixed values or variables that you have created elsewhere in the workflow.
    
-   Optionally, you can also choose variables instead of fixed values for the input parameters.
    
-   Click on the "Submit" button to save the settings.
    

### Additional Options:

When you right-click on the "Sub Workflow" tool in the AIRA Designer workflow, you will encounter five available options:

  


  

1. Unlink:

Purpose: This option allows you to disconnect the "Sub Workflow" tool from any connected apps or tools in the workflow.

Usage: Right-click on the "Sub Workflow" tool and select "Unlink" to remove its connections.

  

2. Setting:

Purpose: Similar to opening the configuration settings by double-clicking, this option provides another way to access and modify the settings of the "Sub Workflow" tool.

Usage: Right-click on the "Sub Workflow" tool and select "Setting" to access its configuration settings.

  

3. Rename:

Purpose: This option enables you to rename the "Sub Workflow" tool, which can help with organisation and clarity within your workflow.

Usage: Right-click on the "Sub Workflow" tool and select "Rename" to change its name.

  

4. Trigger:

Purpose: The "Sub Workflow" option allows you to set triggers on the "Sub Workflow" tool, enabling it to initiate actions based on specified conditions or events.

Usage: Right-click on the "Sub Workflow" tool and select "Trigger" to configure triggers according to your workflow requirements.

  

5. Delete Module:

Purpose: If you no longer need the "Sub Workflow" tool in your workflow, you can use this option to permanently delete it.

Usage: Right-click on the "Sub Workflow" tool and select "Delete Module" to remove it from the workflow.

  

## Switch

The "Switch" tool in AIRA Designer allows users to implement conditional branching within their workflow, directing the flow of actions based on specified conditions. Here's a step-by-step guide on how to use the "Switch" tool:

### How to Use the Switch Tool:


Drag and Drop: Find the "Switch" tool in the Tools Section of the AIRA Designer interface. Drag the "Switch" tool onto your workflow canvas.

  

Connect: Connect the "Switch" tool to the required place in your workflow where you want to implement conditional branching. This can be done by dragging connection lines from the output of the preceding action to the input of the "Switch" tool.

  

Configure Switch:

  

-   Double-click on the "Switch" tool to configure its settings.
    
-   Enter the expression for the logic of the switch process. This expression includes operators like (>,<,= etc) and provides a value activity format which includes variables also, where you define conditions and their corresponding actions.
    
-   Define the conditions and specify the actions to be taken for each condition.
    
-   Ensure that the expression accurately captures the logic for directing the workflow based on the specified conditions.
    
-   Click on the "Submit" button to save the configuration.
    

### Additional Options:

When you right-click on the "Switch" tool in the AIRA Designer workflow, you will encounter five available options:

  

1. Unlink:

Purpose: This option allows you to disconnect the "Switch" tool from any connected apps or tools in the workflow.

Usage: Right-click on the "Switch" tool and select "Unlink" to remove its connections.

  

2. Setting:

Purpose: Similar to opening the configuration settings by double-clicking, this option provides another way to access and modify the settings of the "Switch" tool.

Usage: Right-click on the "Switch" tool and select "Setting" to access its configuration settings.

  

3. Rename:

Purpose: This option enables you to rename the "Switch" tool, which can help with organisation and clarity within your workflow.

Usage: Right-click on the "Switch" tool and select "Rename" to change its name.

  

4. Trigger:

Purpose: The "Switch" option allows you to set triggers on the "Switch" tool, enabling it to initiate actions based on specified conditions or events.

Usage: Right-click on the "Switch" tool and select "Trigger" to configure triggers according to your workflow requirements.

  

5. Delete Module:

Purpose: If you no longer need the "Switch" tool in your workflow, you can use this option to permanently delete it.

Usage: Right-click on the "Switch" tool and select "Delete Module" to remove it from the workflow.

## Join and Fork Join

The "Join" and "Fork Join" tools in AIRA Designer are used together to manage parallel execution of multiple tasks or apps within a workflow. Here's a step-by-step guide on how to use them:

### How to Use Fork Join and Join:


Drag and Drop Fork Join:

  

-   Find the "Fork Join" tool in the Tools Section of the AIRA Designer interface.
    
-   Drag the "Fork Join" tool onto your workflow canvas.
    
-   Connect the "Fork Join" tool to the required place in your workflow where you want to initiate parallel execution of tasks.
    

  

Connect Apps to Fork Join:

  

-   Identify all the apps or tasks that you want to run in parallel.
    
-   Connect each of these apps to the "Fork Join" tool. Each connection represents a branch of the parallel execution.
    

  

Drag and Drop Join:

  

-   Find the "Join" tool in the Tools Section of the AIRA Designer interface.
    
-   Drag the "Join" tool onto your workflow canvas.
    
-   Connect the "Join" tool to the end point of each branch of the parallel execution, i.e., connect it to the outputs of the apps connected to the "Fork Join" tool.
    

### Additional Options:

When you right-click on the "Switch" tool in the AIRA Designer workflow, you will encounter five available options:

  

1. Unlink:

Purpose: This option allows you to disconnect the "Join and Fork Join" tool from any connected apps or tools in the workflow.

Usage: Right-click on the "Join and Fork Join" tool and select "Unlink" to remove its connections.

  

2. Setting:

Purpose: Similar to opening the configuration settings by double-clicking, this option provides another way to access and modify the settings of the "Join and Fork Join" tool.

Usage: Right-click on the "Join and Fork Join" tool and select "Setting" to access its configuration settings.

  

3. Rename:

Purpose: This option enables you to rename the "Join and Fork Join" tool, which can help with organisation and clarity within your workflow.

Usage: Right-click on the "Join and Fork Join" tool and select "Rename" to change its name.

  

4. Trigger:

Purpose: The "Join and Fork Join" option allows you to set triggers on the "Join and Fork Join" tool, enabling it to initiate actions based on specified conditions or events.

Usage: Right-click on the "Join and Fork Join" tool and select "Trigger" to configure triggers according to your workflow requirements.

  

5. Delete Module:

Purpose: If you no longer need the "Join and Fork Join" tool in your workflow, you can use this option to permanently delete it.

Usage: Right-click on the "Join and Fork Join" tool and select "Delete Module" to remove it from the workflow.

  

In conclusion, the diverse array of AIRA tools within the Tools Section empowers users to customise workflows with intelligent logic, enhance efficiency, and streamline processes. Mastering these tools is crucial for maximising productivity and achieving desired outcomes within the AIRA platform.

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
