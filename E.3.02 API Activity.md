<h1><span style="color: #411d66;">Overview                                                     <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e"></span></h1>


<h2 id="api-call-overview" class="toc-header">API Call Overview</h2>
The API Call app in AIRA allows users to interact with external APIs by making HTTP requests. It supports various HTTP methods such as GET, PUT, POST, and PATCH, enabling users to retrieve data, update resources, create new resources, or partially update existing resources.
<h2 id="api-authentication-overview" class="toc-header">API Authentication Overview</h2>
The API Authentication app in AIRA facilitates secure access to external APIs by providing authentication mechanisms. It supports different types of authentication, including API key, basic authentication, OAuth 2.0, and no authorization. This ensures that only authorised users or applications can access the APIs.
<h3 id="use-in-aira" class="toc-header">Use in AIRA</h3>
<ul>
 	<li>Both apps play crucial roles in integrating AIRA workflows with external systems and services.</li>
 	<li>The API Call app enables the execution of API requests to perform various operations, such as fetching data from external sources or updating remote resources.</li>
 	<li>The API Authentication app ensures secure communication with external APIs by handling authentication protocols, thereby safeguarding sensitive data and resources.</li>
 	<li>Together, these apps empower users to automate complex processes, interact with external systems, and leverage the capabilities of external APIs within AIRA workflows.</li>
</ul>
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h3 id="to-use-api-calls-in-aira-follow-these-steps" class="toc-header">To use API calls in AIRA, follow these steps</h3>
<ul>
 	<li>Navigate to the API App in the AIRA app section.</li>
 	<li>Click on API, where you'll find two options: API Authentication and API Call.</li>
 	<li>Drag and drop the API call app into the AIRA workflow designer.</li>
 	<li>Connect the app to the desired location within the workflow.</li>
 	<li>Double-click on the app to open the app setting.</li>
 	<li>Select the method of API Authorization: GET, PUT, POST, or PATCH.</li>
 	<li>Insert the URL. You can use variables to dynamically populate the URL.</li>
 	<li>Insert the parameter, header, and body. Variables can also be used to fill these details.</li>
 	<li>Choose the type of authorization for the API. Options include:
<ul>
 	<li>No authorization</li>
 	<li>API key</li>
 	<li>Basic authorization</li>
 	<li>OAuth 2.0</li>
</ul>
</li>
 	<li>Select the accepted format: JSON, XML, JavaScript, Form, or PDF.</li>
 	<li>Insert token, username, password, key, and value. Variables can be used to insert these details.</li>
 	<li>Click on the submit button to save.</li>
</ul>
<strong>Additional Options:</strong>

Right-click on the app in the AIRA Designer workflow to access additional options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the app from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the app.</li>
 	<li><strong>Rename:</strong> Change the name of the apps for better organization.</li>
 	<li><strong>Trigger</strong>: Set triggers on the app to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the app from the workflow if it's no longer needed.</li>
</ul>
<h3 id="to-use-api-authentication-in-aira-follow-these-steps" class="toc-header">To use API Authentication in AIRA, follow these steps:</h3>
<ul>
 	<li>Navigate to the API App in the AIRA app section.</li>
 	<li>Click on API, where you'll find two options: API Authentication and API Call.</li>
 	<li>Drag and drop the API Authentication app into the AIRA workflow designer.</li>
 	<li>Connect the app to the desired location within the workflow.</li>
 	<li>Double-click on the app to open the app settings.</li>
 	<li>Select the method of API Authorization: GET, PUT, POST, or PATCH
<ul>
 	<li><strong>GET:</strong> Retrieve data from the server.</li>
 	<li><strong>PUT:</strong> Update or replace existing server resources.</li>
 	<li><strong>POST:</strong> Create new resources or submit data for processing.</li>
 	<li><strong>PATCH:</strong> Update existing server resources partially.</li>
</ul>
</li>
 	<li>Insert the URL. You can use variables to dynamically populate the URL.</li>
 	<li>Choose the type of authorization for the API. Options include:
<ul>
 	<li>No authorization</li>
 	<li>API key</li>
 	<li>Basic authorization</li>
 	<li>OAuth 2.0</li>
</ul>
</li>
 	<li>Select the accepted format: JSON, XML, JavaScript, or Form.</li>
 	<li>Fill in the header for the API authentication. Variables can be used here.</li>
 	<li>Fill in the body for the API authentication. Variables can also be used.</li>
 	<li>Fill in the username, password, key, and value for the API authentication. Variables can be utilised for dynamic data.</li>
 	<li>Select the "Add to" option. You can choose to add to either headers or query parameters.</li>
 	<li>Click the submit button to save the settings.</li>
</ul>
<strong>Additional Options:</strong>

Right-click on the apps in the AIRA Designer workflow to access additional options:
<ul>
 	<li><strong>Unlink:</strong> Disconnect the app from any connected apps or tools in the workflow.</li>
 	<li><strong>Setting:</strong> Access and modify the settings of the app.</li>
 	<li><strong>Rename:</strong> Change the name of the apps for better organization.</li>
 	<li><strong>Trigger:</strong> Set triggers on the app to initiate actions based on specified conditions or events.</li>
 	<li><strong>Delete Module:</strong> Permanently delete the app from the workflow if it's no longer needed.</li>
</ul>
&nbsp;

----
![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
