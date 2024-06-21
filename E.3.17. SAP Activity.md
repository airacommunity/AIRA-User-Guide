<h1><span style="color: #411d66;">Overview                                                      <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e"></span></h1>


SAP (Systems, Applications, and Products) is an enterprise resource planning (ERP) software that helps businesses manage various aspects such as finance, operations, human resources, and more.
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h2 id="sap-bapi-nwrfc" class="toc-header">SAP BAPI NWRFC</h2>
SAP Business Application Programming Interface (BAPI) Non-Unicode Remote Function Call (NWRFC) is a technology that allows external systems to communicate with SAP systems and execute remote function calls.
<h3 id="use-in-aira-workflow" class="toc-header">Use in AIRA Workflow</h3>
SAP BAPI NWRFC can be used in AIRA workflows to integrate SAP functionalities into automated processes, enabling seamless data exchange and interaction between SAP systems and other applications.
<h4 id="to-use-sap-bapi-nwrfc-in-aira-follow-these-steps" class="toc-header">To use SAP BAPI NWRFC in AIRA, follow these steps:</h4>
<ol>
 	<li>Navigate to the SAP section in the AIRA app section.</li>
 	<li>Click on SAP, where you'll find two options: SAP BAPI NWRFC and SAP WSDL Calls.</li>
 	<li>Drag and drop the SAP BAPI NWRFC app into the AIRA workflow designer.</li>
 	<li>Connect the app to the desired location within the workflow.</li>
 	<li>Double-click on the app to open the app settings.</li>
 	<li>Select the required connection to establish the connection between SAP and AIRA.</li>
 	<li>If Connection is not available click on add button to create a new connection. To know more about connections visit AIRA <a class="is-external-link" href="https://github.com/airacommunity/AIRA-User-Guide/blob/main/G.%20Connections.md">Connections</a>.</li>
 	<li>Fill in the SAP BAPI name in the designated section. You can use variables to dynamically populate the SAP BAPI name.</li>
 	<li>Provide the SAP BAPI structure. Again, variables can be used to dynamically fill the SAP BAPI structure.</li>
 	<li>Click on the submit button to save the app settings.</li>
</ol>
<strong>Additional Options:</strong>

Right-click on the app in the AIRA Designer workflow to access additional options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the app from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the app.</li>
 	<li><strong>Rename:</strong> Change the name of the apps for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the app to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the app from the workflow if it's no longer needed.</li>
</ul>
<h2 id="sap-wsdl-calls" class="toc-header">SAP WSDL Calls</h2>
SAP WSDL (Web Services Description Language) Calls allow AIRA workflows to invoke SAP's web services and execute specific functions or operations within the SAP system.
<h3 id="use-in-aira-workflow-1" class="toc-header">Use in AIRA Workflow</h3>
SAP WSDL Calls facilitate the integration of SAP web services into AIRA workflows, enabling automated interactions with SAP systems to perform tasks such as data retrieval, updates, and more.

Working Together in AIRA: SAP BAPI NWRFC and SAP WSDL Calls work together within AIRA workflows to enable comprehensive integration with SAP systems. BAPI NWRFC facilitates direct communication with SAP systems, while WSDL Calls enable interaction with SAP's web services, collectively allowing for seamless integration and automation of SAP-related tasks within the AIRA platform.
<h4 id="to-use-sap-wsdl-calls-in-aira-follow-these-steps" class="toc-header">To use SAP WSDL calls in AIRA, follow these steps:</h4>
<ol>
 	<li>Navigate to the SAP section in the AIRA app section.</li>
 	<li>Click on SAP, where you'll find two options: SAP BAPI NWRFC and SAP WSDL Calls.</li>
 	<li>Drag and drop the SAP WSDL call app into the AIRA workflow designer.</li>
 	<li>Connect the app to the desired location within the workflow.</li>
 	<li>Double-click on the app to open its settings.</li>
 	<li>Fill in the request URL. You can use variables to dynamically populate the request URL.</li>
 	<li>Select the request method. Choose from GET, PUT, POST, PATCH, or DELETE based on your requirements.</li>
 	<li>Understand the use of each request method:
<ul>
 	<li><strong>GET:</strong> Retrieve data from the server.</li>
 	<li><strong>PUT:</strong> Update data on the server.</li>
 	<li><strong>POST</strong>: Send data to the server to create a new resource.</li>
 	<li><strong>PATCH</strong>: Update specific parts of data on the server.</li>
 	<li><strong>DELETE</strong>: Remove data from the server.</li>
</ul>
</li>
 	<li>Select the appropriate authorization method: no authorization, basic authorization, or bearer token.</li>
 	<li>Fill in the body of the request. Variables can be used to dynamically populate the request body.</li>
 	<li>Enter the username. Variables can also be used here.</li>
 	<li>Provide the password.</li>
 	<li>Click on the submit button to save the app settings.</li>
</ol>
<strong>Additional Options:</strong>

Right-click on the app in the AIRA Designer workflow to access additional options:
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
