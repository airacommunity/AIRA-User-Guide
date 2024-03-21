# AIRA Tools

## Overview

  

The Tools Section is the powerhouse of capabilities designed to elevate your workflow by providing robust logic-building tools. It serves as your go-to destination for infusing intelligence and logic into your workflows, empowering users to define the flow and decision points to ensure a customised and efficient process.

  

![](https://lh7-us.googleusercontent.com/9WpTsJMHtYIqHY7PaHMZhfN8H0pjC8vAkIqq2d3oyezCO0z0ViyoGRMFN1I2vo46kFglas-3Z9nn-VK5d7Oke5tS2W5OY--OWi9X00yzue8DZGYZ_vzp0xqBe0ctIMrSYJjFJGHkP0VG2qmluBgU0XI)

  

Within the Tools Section, you'll find a diverse array of tools, each crafted to address specific workflow needs. These tools collectively contribute to enhancing the overall functionality of your workflows. Here's the detail explanation of the tools and how to use it :

## WAIT

The "Wait" tool enables users to specify a duration of time for the workflow to pause before proceeding to the next step. This pause can be based on either a specific date and time or a relative time period, such as waiting for a certain number of minutes, hours, or days.

### How to Use the "Wait" Tool:

Drag and Drop

![](https://lh7-us.googleusercontent.com/vIBYlMgpdX_zK4Fvmc9D7CZ6aKUuRFyqUy1BMMGAo1L-T0W5dy1l-eRWP4Dsb6RISITP59ww5xMYZ4S4FgqIhNdn5IOQ2lQP4igAeg1FdfwXfSkL2ZfpLcRqAHAqUOves7KnDAGhga6qEfKgxqjUb7Y)

Begin by locating the "Wait" tool in the Tools Section of the AIRA Designer interface. Drag the "Wait" tool onto the workflow canvas.

  

Connect

![](https://lh7-us.googleusercontent.com/q_7icl0rJvsAoa3G589XG9RTl2hrk6gv7Hbg0d4oPXUGLFIKk3QakIVXn-A3uyVG0mLvyKJ1ynZJxFbygTlC4aCs_XoOYPw9nLcC1f3YCMrwkGy5pV67777UX2F6Qkd6fQoklMjnvTKYY7anU1vf89E)

Connect the "Wait" tool between the two actions or steps where you want to introduce a delay. This can be done by dragging a connection line from the output of the preceding action to the input of the "Wait" tool, and then from the output of the "Wait" tool to the input of the subsequent action.

  

Configure:

Double-click on the "Wait" tool to open its settings.

  

WAIT-FOR Option:

Purpose: The "WAIT-FOR" option allows you to specify a relative time duration to wait before proceeding with the workflow.

  

![](https://lh7-us.googleusercontent.com/ybDcw2-BuvWDid9ugxBw4hlFwN-zynLytPktTyqBUf60NKWHTnhj9BZWBPibSdelLD76NmKDswI7SqnyrdupPBJoELxXH5-Qt23lCQ5cHOC_LZ-x3GjK6sfaFTHAUbYG3B_RWnm42q2KqinK39Jrlag)

  

Steps:

-   Select the Tool: Double-click on the "Wait" tool to open its settings.
    
-   Choose WAIT-FOR: Select the "WAIT-FOR" option from the settings menu.
    
-   Fill Details:
    
-   Enter the desired number of days, hours, and minutes to wait before proceeding.
    
-   For example, if you want to wait for 1 day, 2 hours, and 30 minutes, enter these values in their respective fields.
    
-   Submit: Click on the "Submit" button to save the settings.
    

  

WAIT-SPECIFIED-DATE-TIME Option :  
Purpose: The "WAIT-SPECIFIED-DATE-TIME" option allows you to specify an exact date and time to wait until before proceeding with the workflow.

  

Steps:

  

![](https://lh7-us.googleusercontent.com/o-1dUWtYJvB_5WA0faC50ad44sq2Ddvaf98Q8v1Eol78KMPJf_xwEzVlZtWjv2Sjssq_aPk9p15vdGvv4Dx3SDvfA8SbgbGbvub1aKPqJtWf_QJLIhKygmL5B2qn-kLPUp67G5SoknDrrlZP1bHUDW0)

  

-   Select the Tool: Double-click on the "Wait" tool to open its settings.
    
-   Choose WAIT-SPECIFIED-DATE-TIME: Select the "WAIT-SPECIFIED-DATE-TIME" option from the settings menu.
    
-   Enter Date and Time:
    
-   Enter the specific date and time you want to wait until before proceeding.
    
-   Ensure the format is correct, including the date, time, and time zone if applicable.
    
-   Submit: Click on the "Submit" button to save the settings.
    

### Additional Options:

When you right-click on the "Wait" tool in the AIRA Designer workflow, you will encounter five available options:

  

![](https://lh7-us.googleusercontent.com/jSG7kqSTI21cTcl1SEOR9j8TQY0WsrR8_MQDrDgB43UIFgLHhvuCh6VAdXhWo0jej2VXEEY-9JSEE2Fbnn9yByug1nMWfH7yCkrJotyJwJJHvDxZkUXGNBBlD6s43p4rsk3BhTWjMogNk-3bfZqzo8A)

  

1. Unlink :

Purpose: This option allows you to disconnect the "Wait" tool from any connected apps or tools in the workflow.

Usage: Right-click on the "Wait" tool and select "Unlink" to remove its connections.

  

2. Setting :

Purpose: Similar to opening the configuration settings by double-clicking, this option provides another way to access and modify the settings of the "Wait" tool.

Usage: Right-click on the "Wait" tool and select "Setting" to access its configuration settings.

  

3. Rename :

Purpose: This option enables you to rename the "Wait" tool, which can help with organisation and clarity within your workflow.

Usage: Right-click on the "Wait" tool and select "Rename" to change its name.

  

4. Trigger :

Purpose: The "Trigger" option allows you to set triggers on the "Wait" tool, enabling it to initiate actions based on specified conditions or events.

Usage: Right-click on the "Wait" tool and select "Trigger" to configure triggers according to your workflow requirements.

  

5. Delete Module:

Purpose: If you no longer need the "Wait" tool in your workflow, you can use this option to permanently delete it.

Usage: Right-click on the "Wait" tool and select "Delete Module" to remove it from the workflow.

## Terminate

The "Terminate" tool in the AIRA Designer workflow is used to abruptly end a process or task before its natural completion. Here's a step-by-step guide on how to use the "Terminate" tool:

### How to Use the Terminate Tool:

Drag and Drop: Find the "Terminate" tool in the Tools Section of the AIRA Designer interface. Drag the "Terminate" tool onto your workflow canvas.

  

Connect: Connect the "Terminate" tool to the app or tool where you want to apply the termination. This can be done by dragging a connection line from the output of the preceding action to the input of the "Terminate" tool.

  

Configure:

  

![](https://lh7-us.googleusercontent.com/BSDs2aFJJUJCDyXvaeYbsjju9fPydzZLi7A8bBtQiVLy1t3HQhTY2TblHaR0zykVqtgDZiprGsBVdRRnZHcO_HPa4iZ8ZDCcrpDLzE-odzTTnd-FgvzbNaReJo2XlMcdhygxyciWre0jl9AkDXsSd50)

  

-   Double-click on the "Terminate" tool to open its settings.
    
-   Set the Status: Choose between "Completed" or "Failed" to indicate the status of the terminated process. This helps to clarify whether the process was successfully completed or not.
    
-   Define the Output: Specify what output or result should be provided after the termination of the process. This could be a specific value or a variable that you've defined elsewhere in the workflow.
    
-   Provide a Termination Reason: Describe the reason for the termination, which can help with debugging or understanding the workflow. This can be a fixed value or a variable.
    
-   Click on the "Submit" button to save the settings.
    

### Additional Options:

When you right-click on the "Terminate" tool in the AIRA Designer workflow, you will encounter five available options:

  

![](https://lh7-us.googleusercontent.com/bR-OszOM1uILHIw8DpWxeZJZyXskPcwThxU4AyaFFiE33OeCkoHjFHP0Uwhm3tIGWemrnjYxWtOdGXbQVx4eWkqoaT4cPHryTngrHvy9Wz6ffxTNOpEgewtuHgaD4Q7FEnopDuJQ27z5I-u1SH48yfQ)

  

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

![](https://lh7-us.googleusercontent.com/ZuG43Elp8swfm4xhD1nA7SHYfs5H7Y60cX45bQGBa4Z7nQ2DZ2FhrGDjLbOToISTaDvCr1yBeY45a5E8-OyC5ZFxIi2GvWiMSuO5U2YpxkpI7Cy5SACVPNjNmk08kZ2i7J0SgEvzx-WFwAypHFzAD8o)

  

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

![](https://lh7-us.googleusercontent.com/yqQeC7tf9LFgermffAyDQxx4rElMRDU5gtGaRu5MILxE7tS14hjP8SM9ANWP2M6CUmaVRTAW8VeIBTV1TItObc_JURp0YfIqVV0yU92HYJDLNwxSoz8IR-ZzaAmDZfLTGQYnZxk4UWKvzJ76e-VcsXM)

Drag and Drop: Locate the "Do While" tool in the Tools Section of the AIRA Designer interface. Drag the "Do While" tool onto your workflow canvas.

  

Connect: Connect the "Do While" tool to the required place in your workflow where you want the loop to begin and end. This can be done by dragging connection lines from the output of the preceding action to the input of the "Do While" tool, and then from the output of the "Do While" tool back to the input of the action where the loop should end.

  

Configure Loop Parameters:

  

-   Drag and drop the app or action that you want to include in the loop into the "Do While" tool. This action will be repeated as long as the specified condition is true.
    
-   Right-click on the "Do While" tool and select "SETTING" to set the loop parameters and condition.
    
-   In the settings, You can place any value in the parameters or choose variables that you have created elsewhere in the workflow.
    
-   Click on the "Submit" button to save the loop parameters and condition.
    

### Additional Options:

When you right-click on the "Do While" tool in the AIRA Designer workflow, you will encounter five available options:

  

![](https://lh7-us.googleusercontent.com/POUyxnAcNLCslfCiVzFJ6cO2QsU92btMwkuVg-iTfm9LoU4GhziJbZs6BF8K6uLjWy7AbfcmoAOxr2UrufgzRqKvSKexnY7wU6zjb76Es8_2jtrQ94gTcJkmoWe5g916C466XtJzzrEAiPiD1ssWFf8)

  

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

![](https://lh7-us.googleusercontent.com/Et6GhKVwMQCiAgqVo7II0759g6w9Rk2dtNUS1Pttmayfi6ERpgcKam-ZeOo5fFJ0l28alGS7LhWfWQ9FdW7O9_nhB9UdF2YWuT-pxT82zVxrZiYaxnYj66_1kWqThD1eZwGkNCKYdiI7fyb5vBadJPY)

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

  

![](https://lh7-us.googleusercontent.com/lC86Rixrsa90LpmBUq2m2m56qByWENcDH3OOc3eoPrT-_aA9SbywZj3vEEJDvVdTUQn9myuzoHfGoAjZ0lWkRoiHytgFO1AQMVUCiTAOd7qZ2ZuJaqh9x40iCk3MAOseEwwWP-pBSc2-KLaiAjOaDwY)

  

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

![](https://lh7-us.googleusercontent.com/q_UHVGS4KREn9oRbprIFyVihmTl0f99E1jfY532He3GmuQ4gJcxSGcmhgQs6R4DCQaN1zZqZ1f61XCRefgDf82DzANSWw4LTNCkTEWftVfmbSr1TrIYc-vDDz58XrGlFsZe93Ue14UuHtO_GzS6p3hw)

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

![](https://lh7-us.googleusercontent.com/tozWiHjQKu1R-gE5fLqTzOWFnYHq6_2fwylSihl2Sx64zLlAmtIyKXHgw-G03ZXpH0aiFr8DbGDoSDpFTprOdqq5BkX3cJ0jZ8hiJM1QmF1ll4Vx70NLXwcxsZDLyxiRziiGYnNPNtd2P28e09rd82w)

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
