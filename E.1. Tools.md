<h1><span style="color: #411d66;">Overview                                                       <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e">
</span></h1>


The Tools Section is the powerhouse of capabilities designed to elevate your workflow by providing robust logic-building tools. It serves as your go-to destination for infusing intelligence and logic into your workflows, empowering users to define the flow and decision points to ensure a customised and efficient process.
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h2 id="exploring-logical-tools-in-aira" class="toc-header">Exploring Logical Tools in AIRA</h2>
<h3 id="fork-join-and-join" class="toc-header">Fork Join and Join</h3>
The "Join" and "Fork Join" tools in AIRA Designer facilitate parallel execution of multiple tasks or applications within a workflow. They enable the simultaneous execution of these tasks and ensure that the workflow progresses to the next activity once all parallel tasks have been completed. This allows for efficient management of concurrent processes within the workflow environment.
<h4 id="how-to-use-the-fork-join-and-join-tools" class="toc-header">How to Use the Fork Join and Join Tools:</h4>
<ul>
 	<li><strong>Drag and Drop Fork Join:</strong>
<ul>
 	<li>Find the "Fork Join" tool in the Tools Section of the AIRA Designer interface.</li>
 	<li>Drag and drop the "Fork Join" tool onto your workflow designer.</li>
 	<li>Connect the "Fork Join" tool to the required place in your workflow where you want to initiate parallel execution of tasks.</li>
</ul>
</li>
 	<li><strong>Connect Apps to Fork Join:</strong>
<ul>
 	<li>Identify all the apps or tasks that you want to run in parallel.</li>
 	<li>Connect each of these apps to the "Fork Join" tool. Each connection represents a branch of the parallel execution.</li>
</ul>
</li>
 	<li><strong>Drag and Drop Join:</strong>
<ul>
 	<li>Find the "Join" tool in the Tools Section of the AIRA Designer interface.</li>
 	<li>Drag and drop the "Join" tool onto your workflow designer.</li>
 	<li>Connect the "Join" tool to the end point of each branch of the parallel execution, i.e., connect it to the outputs of the apps connected to the "Fork Join" tool.</li>
</ul>
</li>
 	<li><strong>Additional Options:</strong>Right-click on the "Join and Fork Join" tool in the AIRA Designer workflow to access additional options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the tools from any connected apps or tools in the workflow.</li>
 	<li><strong>Rename:</strong> Change the name of the tools for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the tools to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the tools from the workflow if it's no longer needed.</li>
</ul>
</li>
</ul>
<h3 id="do-while" class="toc-header">Do While</h3>
The "Do While" tool in the AIRA workflow designer is used to create loop structures within your workflow.
<h4 id="how-to-use-the-do-while-tool" class="toc-header">How to Use the Do While Tool:</h4>
<ul>
 	<li><strong>Drag and Drop:</strong>
<ul>
 	<li>Locate the "Do While" tool in the Tools Section of the AIRA Designer interface.</li>
 	<li>Drag and drop the "Do While" tool onto your workflow designer and Connect the "Do While" tool to the required place in your workflow.</li>
</ul>
</li>
 	<li><strong>Configure Loop:</strong>
<ul>
 	<li>Drag and drop the app that you want to include in the loop into the "Do While" tool. This action will be repeated as long as the specified condition is true.</li>
 	<li>Right-click on the "Do While" tool and select "SETTING" to set the loop parameters.</li>
 	<li>In the settings, you have the flexibility to input any value into the parameters or select variables created elsewhere in the workflow. Parameters define the number of times the loop should execute.</li>
 	<li>Click on the "Submit" button to save the loop parameters.</li>
</ul>
</li>
 	<li><strong>Additional Options:</strong>Right-click on the "Do While" tool in the AIRA Designer workflow to access additional options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the "Do While" tool from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the "Do While" tool.</li>
 	<li><strong>Rename:</strong> Change the name of the "Do While" tool for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the "Do While" tool to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the "Do While" tool from the workflow if it's no longer needed.</li>
</ul>
</li>
</ul>
<h3 id="set-variable" class="toc-header">Set Variable</h3>
The Set Variable tool is a component utilized within workflow design environments to establish and define input variables. By incorporating the Set Variable tool into a workflow and establishing connections with other tools or applications, these downstream elements gain access to the variable generated by the Set Variable tool.
<h4 id="how-to-use-the-set-variable-tool" class="toc-header">How to Use the Set Variable Tool:</h4>
<ul>
 	<li><strong>Drag and Drop:</strong>
<ul>
 	<li>Locate the "Set Variable" tool in the Tools Section of the AIRA Designer interface.</li>
 	<li>Drag and drop the "Set Variable" tool onto your workflow designer.</li>
</ul>
</li>
 	<li><strong>Connect:</strong>
<ul>
 	<li>Connect the "Set Variable" tool to the app or tool where you want to apply the variable.</li>
 	<li>This can be done by dragging a connection line from the output of the preceding action to the input of the "Set Variable" tool.</li>
</ul>
</li>
 	<li><strong>Configure:</strong>
<ul>
 	<li>Double-click on the "Set Variable" tool to open its settings.</li>
 	<li>In the settings, you will find the Input field.</li>
 	<li>Define the Input: Input the information you want to assign to the variable.</li>
 	<li>This could be a specific value, a result from a previous action, or another variable.</li>
 	<li>You can directly enter the value or select a variable from elsewhere in the workflow.</li>
 	<li>Click on the "Submit" button to save the settings.</li>
</ul>
</li>
 	<li><strong>Additional Options:</strong>Right-click on the "Set Variable" tool in the AIRA Designer workflow to access additional options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the "Set Variable" tool from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the "Set Variable" tool.</li>
 	<li><strong>Rename:</strong> Change the name of the "Set Variable" tool for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the "Set Variable" tool to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the "Set Variable" tool from the workflow if it's no longer needed.</li>
</ul>
</li>
</ul>
<h3 id="sub-workflow" class="toc-header">Sub Workflow</h3>
The "Sub Workflow" tool in AIRA Designer allows users to incorporate other workflows within their current workflow, promoting modularity and reusability.
<h4 id="how-to-use-the-sub-workflow-tool" class="toc-header">How to Use the Sub Workflow Tool:</h4>
<ul>
 	<li><strong>Drag and Drop:</strong>
<ul>
 	<li>Locate the "Sub Workflow" tool in the Tools Section of the AIRA Designer interface.</li>
 	<li>Drag and drop the "Sub Workflow" tool onto your workflow designer.</li>
</ul>
</li>
 	<li><strong>Connect:</strong>
<ul>
 	<li>Connect the "Sub Workflow" tool to the required place in your workflow where you want to invoke the subworkflow.</li>
 	<li>Drag connection lines from the output of the preceding action to the input of the "Sub Workflow" tool.</li>
</ul>
</li>
 	<li><strong>Configure Subworkflow:</strong>
<ul>
 	<li>Double-click on the "Sub Workflow" tool to configure its settings.</li>
 	<li>Choose the job or workflow that you want to use within your current workflow.</li>
 	<li>Provide input parameters for the sub workflow by specifying keys and their corresponding values.</li>
 	<li>Optionally, choose variables instead of fixed values for the input parameters.</li>
 	<li>Click on the "Submit" button to save the settings.</li>
</ul>
</li>
 	<li><strong>Additional Options:</strong>Right-click on the "Subworkflow" tool in the AIRA Designer workflow to encounter five available options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the "Sub Workflow" tool from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the "Sub Workflow" tool.</li>
 	<li><strong>Rename:</strong> Change the name of the "Sub Workflow" tool for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the "Sub Workflow" tool to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the "Sub Workflow" tool from the workflow if it's no longer needed.</li>
</ul>
</li>
</ul>
<h3 id="switch" class="toc-header">Switch</h3>
The "Switch" tool in AIRA Designer allows users to implement conditional branching within their workflow, directing the flow of actions based on specified conditions.
<h4 id="how-to-use-the-switch-tool" class="toc-header">How to Use the Switch Tool:</h4>
<ul>
 	<li><strong>Drag and Drop:</strong>
<ul>
 	<li>Find the "Switch" tool in the Tools Section of the AIRA Designer interface.</li>
 	<li>Drag and drop the "Switch" tool onto your workflow designer.</li>
</ul>
</li>
 	<li><strong>Connect:</strong>
<ul>
 	<li>Connect the "Switch" tool to the required place in your workflow where you want to implement conditional branching.</li>
 	<li>This can be done by dragging connection lines from the output of the preceding action to the input of the "Switch" tool and connect output of the switch tool with the multiple apps which you want to switch according to conditions.</li>
</ul>
</li>
 	<li><strong>Open Switch Configuration:</strong>
<ul>
 	<li>Locate the "Switch" tool in your workflow.</li>
 	<li>Double-click on the "Switch" tool to access its configuration settings.</li>
</ul>
</li>
 	<li><strong>Define Logic Expression:</strong>
<ul>
 	<li>Within the configuration window, locate the expression field for defining the logic of the switch process.</li>
 	<li>Construct an expression that encapsulates the conditions and actions for directing the workflow.</li>
 	<li>Utilize operators such as greater than (&gt;), less than (&lt;), equal to (=), etc., within the expression.</li>
 	<li>Incorporate variables within the expression to enable dynamic evaluation</li>
 	<li><code>For example: $$workflow.variables.result.age$$ &gt;= 12</code></li>
</ul>
</li>
 	<li><strong>Ensure Accuracy:</strong>
<ul>
 	<li>Review the expression to ensure it accurately captures the intended logic for directing the workflow.</li>
 	<li>Verify that all conditions and corresponding actions are appropriately defined.</li>
</ul>
</li>
 	<li><strong>Set Branching Conditions:</strong>
<ul>
 	<li>After defining the expression, proceed to set the operator and conditions for branching applications or tools.</li>
 	<li>Optionally, apply logical operators such as AND and OR to combine multiple branching conditions.</li>
</ul>
</li>
 	<li><strong>Submit Configuration:</strong>
<ul>
 	<li>Once satisfied with the configuration, click on the "Submit" button to save the settings.</li>
</ul>
</li>
 	<li><strong>Additional Options:</strong>Right-click on the "Switch" tool in the AIRA Designer workflow to encounter five available options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the "Swtich" tool from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the "Switch" tool.</li>
 	<li><strong>Rename:</strong> Change the name of the "Switch" tool for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the "Switch" tool to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the "Switch" tool from the workflow if it's no longer needed.</li>
</ul>
</li>
</ul>
<h3 id="terminate" class="toc-header">Terminate</h3>
Terminate refers to a tool used to abruptly stop a process or task before it finishes naturally. This tool is handy when there's a need to halt an operation due to an error, a specific condition, or as part of the planned workflow logic. By activating "Terminate," the ongoing task immediately ceases, preventing any further actions from taking place. This feature offers control and flexibility, enabling users to manage workflow flow according to specific needs and circumstances.
<h4 id="how-to-use-the-terminate-tool" class="toc-header">How to Use the Terminate Tool</h4>
<ul>
 	<li><strong>Drag and Drop:</strong>
<ul>
 	<li>Find the "Terminate" tool in the Tools Section of the AIRA Designer interface.</li>
 	<li>Drag and drop the "Terminate" tool onto your workflow designer.</li>
</ul>
</li>
 	<li><strong>Connect:</strong>
<ul>
 	<li>Connect the "Terminate" tool to the app or tool where you want to apply the termination.</li>
 	<li>This can be done by dragging a connection line from the output of the preceding action to the input of the "Terminate" tool.</li>
</ul>
</li>
 	<li><strong>Configure:</strong>
<ul>
 	<li>Double-click on the "Terminate" tool to open its settings.</li>
 	<li>Set the Status: Choose between "Completed" or "Failed" to indicate the status of the terminated process.</li>
 	<li>Define the Output: Specify what output or result should be provided after the termination of the process.</li>
 	<li>Provide a Termination Reason: Describe the reason for the termination.</li>
 	<li>Click on the "Submit" button to save the settings.</li>
</ul>
</li>
 	<li><strong>Additional Options:</strong>Right-click on the "Terminate" tool in the AIRA Designer workflow to encounter five available options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the "Terminate" tool from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the "Terminate" tool.</li>
 	<li><strong>Rename:</strong> Change the name of the "Terminate" tool for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the "Terminate" tool to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the "Terminate" tool from the workflow if it's no longer needed.</li>
</ul>
</li>
</ul>
<h3 id="wait" class="toc-header">WAIT</h3>
The "Wait" tool enables users to specify a duration of time for the workflow to pause before proceeding to the next step. This pause can be based on either a specific date and time or a relative time period, such as waiting for a certain number of minutes, hours, or days.
<h4 id="how-to-use-the-wait-tool" class="toc-header">How to Use the "Wait" Tool</h4>
<ul>
 	<li><strong>Drag and Drop:</strong>
<ul>
 	<li>Go to the Tools Section of the AIRA Designer interface.</li>
 	<li>Find the "Wait" tool, drag &amp; drop it onto the workflow designer.</li>
</ul>
</li>
 	<li><strong>Connect:</strong>
<ul>
 	<li>Drag a connection line from the output of the preceding action to the input of the "Wait" tool.</li>
 	<li>Then, drag a connection line from the output of the "Wait" tool to the input of the subsequent action.</li>
</ul>
</li>
 	<li><strong>WAIT FOR - Configure:</strong>
<ul>
 	<li><strong>Select the Tool:</strong> Double-click on the "Wait" tool to open its settings.</li>
 	<li><strong>Choose WAIT-FOR:</strong>
<ul>
 	<li>Select the "WAIT-FOR" option from the settings menu.</li>
</ul>
</li>
 	<li><strong>Fill Details:</strong>
<ul>
 	<li>Enter the desired number of days, hours, and minutes to wait before proceeding.</li>
 	<li>For example, if you want to wait for 1 day, 2 hours, and 30 minutes, enter these values in their respective fields.</li>
</ul>
</li>
 	<li><strong>Submit:</strong>
<ul>
 	<li>Click on the "Submit" button to save the settings.</li>
</ul>
</li>
</ul>
</li>
 	<li><strong>WAIT-SPECIFIED-DATE-TIME - Configure:</strong>
<ul>
 	<li><strong>Select the Tool:</strong> Double-click on the "Wait" tool to open its settings.</li>
 	<li><strong>Choose WAIT-SPECIFIED-DATE-TIME:</strong>
<ul>
 	<li>Select the "WAIT-SPECIFIED-DATE-TIME" option from the settings menu.</li>
</ul>
</li>
 	<li><strong>Enter Date and Time:</strong>
<ul>
 	<li>Enter the specific date and time you want to wait until before proceeding.</li>
 	<li>Ensure the format is correct, including the date, time, and time zone if applicable.</li>
</ul>
</li>
</ul>
</li>
 	<li><strong>Submit:</strong>
<ul>
 	<li>Click on the "Submit" button to save the settings.</li>
</ul>
</li>
 	<li><strong>Additional Options:</strong>When right-clicking on the "Wait" tool in the AIRA Designer workflow, you'll encounter five available options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the "Wait" tool from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the "Wait" tool.</li>
 	<li><strong>Rename:</strong> Change the name of the "Wait" tool for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the "Wait" tool to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the "Wait" tool from the workflow if it's no longer needed.</li>
</ul>
</li>
</ul>
&nbsp;

----
![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
