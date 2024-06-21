<h1><span style="color: #411d66;">Overview                                                     <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e"></span></h1>


SFTP, which stands for Secure File Transfer Protocol, is a network protocol used to securely transfer files over a computer network. It's designed to ensure that data is protected during transmission by encrypting files, making it difficult for unauthorised users to access or intercept them.

In AIRA, SFTP plays a crucial role in securely uploading files to remote systems or downloading them onto the local system. This is particularly important for transferring sensitive data like automation scripts and configuration files between users and the AIRA platform. By using SFTP, we ensure that the transfer process maintains data integrity and confidentiality, safeguarding information from potential security threats.
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h3 id="accessing-the-sftp-app" class="toc-header">Accessing the SFTP App:</h3>
<ul>
 	<li>Click on the module section within the AIRA workflow designer.</li>
 	<li>The app section will be displayed at the top of the module section.</li>
 	<li>Select the SFTP app. It offers two options: "Get Files" and "Put Files".</li>
</ul>
<h3 id="get-files-option" class="toc-header">Get Files Option:</h3>
<ul>
 	<li>This option is used to download files from remote locations to the local system.</li>
 	<li>To use the app, simply drag and drop it into the workflow designer.</li>
 	<li>After adding the app, double-click on it to configure its settings.</li>
</ul>
<h3 id="configuration" class="toc-header">Configuration:</h3>
<ul>
 	<li>Connection: Choose a valid connection for importing files from the remote to the local system.</li>
 	<li>If Connection is not available click on add button to create a new connection. To know more about connections visit AIRA <a class="is-external-link" href="https://wiki.aira.fr/docs/connections/">Connections</a>.</li>
 	<li>Remote Path: Enter a valid remote path for importing files. You can also use variables if the remote path is stored in any.</li>
 	<li>Local Path: Specify a valid local path for importing files. Variables can also be used if the local path is stored elsewhere.</li>
 	<li>Click on the submit button to save the configuration. To cancel and discard changes, use the cancel button next to the submit button.</li>
</ul>
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

----
![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
