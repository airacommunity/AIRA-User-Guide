![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# SAP Activity <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">

## Overview
SAP (Systems, Applications, and Products) is an enterprise resource planning (ERP) software that helps businesses manage various aspects such as finance, operations, human resources, and more.

<br>

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/Icon-Warning.png?raw=true"> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

<br>

## SAP BAPI NWRFC

SAP Business Application Programming Interface (BAPI) Non-Unicode Remote Function Call (NWRFC) is a technology that allows external systems to communicate with SAP systems and execute remote function calls.

  

### Use in AIRA Workflow

SAP BAPI NWRFC can be used in AIRA workflows to integrate SAP functionalities into automated processes, enabling seamless data exchange and interaction between SAP systems and other applications.

  

## SAP WSDL Calls

SAP WSDL (Web Services Description Language) Calls allow AIRA workflows to invoke SAP's web services and execute specific functions or operations within the SAP system.

  

### Use in AIRA Workflow

SAP WSDL Calls facilitate the integration of SAP web services into AIRA workflows, enabling automated interactions with SAP systems to perform tasks such as data retrieval, updates, and more.

  

Working Together in AIRA: SAP BAPI NWRFC and SAP WSDL Calls work together within AIRA workflows to enable comprehensive integration with SAP systems. BAPI NWRFC facilitates direct communication with SAP systems, while WSDL Calls enable interaction with SAP's web services, collectively allowing for seamless integration and automation of SAP-related tasks within the AIRA platform.

  

#### To use SAP BAPI NWRFC in AIRA, follow these steps:

  

1. Navigate to the SAP section in the AIRA app section.

2. Click on SAP, where you'll find two options: SAP BAPI NWRFC and SAP WSDL Calls.

3. Drag and drop the SAP BAPI NWRFC app into the AIRA workflow designer.

4. Connect the app to the desired location within the workflow.

5. Double-click on the app to open the app settings.

6. Select the required connection to establish the connection between SAP and AIRA.

7. Fill in the SAP BAPI name in the designated section. You can use variables to dynamically populate the SAP BAPI name.

8. Provide the SAP BAPI structure. Again, variables can be used to dynamically fill the SAP BAPI structure.

9. Click on the submit button to save the app settings.

  

**Additional Options:**

Right-click on the app in the AIRA Designer workflow to access additional options:

- Unlink: Disconnect the app from any connected apps or tools in the workflow.
- Setting: Access and modify the settings of the app.
- Rename: Change the name of the apps for better organization.
- Trigger: Set triggers on the app to initiate actions based on specified conditions or events.
- Delete Module: Permanently delete the app from the workflow if it's no longer needed.
  

#### To use SAP WSDL calls in AIRA, follow these steps:

  

1. Navigate to the SAP section in the AIRA app section.

2. Click on SAP, where you'll find two options: SAP BAPI NWRFC and SAP WSDL Calls.

3. Drag and drop the SAP WSDL call app into the AIRA workflow designer.

4. Connect the app to the desired location within the workflow.

5. Double-click on the app to open its settings.

6. Fill in the request URL. You can use variables to dynamically populate the request URL.

7. Select the request method. Choose from GET, PUT, POST, PATCH, or DELETE based on your requirements.

8. Understand the use of each request method:

GET: Retrieve data from the server.

PUT: Update data on the server.

POST: Send data to the server to create a new resource.

PATCH: Update specific parts of data on the server.

DELETE: Remove data from the server.

9. Select the appropriate authorization method: no authorization, basic authorization, or bearer token.

10. Fill in the body of the request. Variables can be used to dynamically populate the request body.

11. Enter the username. Variables can also be used here.

12. Provide the password.

13. Click on the submit button to save the app settings.

  

**Additional Options:**

Right-click on the app in the AIRA Designer workflow to access additional options:

- Unlink: Disconnect the app from any connected apps or tools in the workflow.
- Setting: Access and modify the settings of the app.
- Rename: Change the name of the apps for better organization.
- Trigger: Set triggers on the app to initiate actions based on specified conditions or events.
- Delete Module: Permanently delete the app from the workflow if it's no longer needed.

----

> To proceed with your exploration, just click the 'Next' button to seamlessly move on to the next section.

----


<table align="right" border="0">
    <tr>
      <td align="center"><a href="https://github.com/airacommunity/AIRA-User-Guide/blob/main/A.%20Introduction%20to%20AIRA%20User%20Guide.md"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-previous.png" alt="Image 5" width="40" height="40"></a></td>
      <td align="center"><a href="https://github.com/airacommunity/AIRA-User-Guide/blob/main/C.%20Introduction%20to%20AIRA%20Installation.md"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-next.png" alt="Image 5" width="40" height="40"></a></td>
    </tr>
</table>

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
