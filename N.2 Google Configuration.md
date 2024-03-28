![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# Google Cloud Platform <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">

## Overview
GCP stands for Google Cloud Platform, which is a suite of cloud computing services offered by Google. It provides various infrastructure and platform services for computing, storage, data analytics, machine learning, and more, allowing organisations to build, deploy, and scale applications and services on Google's infrastructure.


<br>

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-caution.jpg?raw=true"> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

<br>

### Google API

GCP API services refer to the application programming interfaces (APIs) provided by Google Cloud Platform for accessing and interacting with specific Google services, such as Google Sheets, Google Drive, Google Calendar, and Gmail. These APIs enable developers to integrate Google services into their applications, automate workflows, and access data stored in Google's cloud services programmatically.

### GCP API In AIRA
In AIRA, GCP API services are used to integrate Google services seamlessly into the AIRA platform, enhancing its functionality and enabling users to leverage the capabilities of Google's services within their workflows. 

- **Google Sheets API:** Allows users to read, write, and manipulate data in Google Sheets directly from AIRA workflows, enabling automated data processing and analysis.

- **Google Drive API:** Enables users to access files and folders stored in Google Drive, upload and download files, and manage permissions, facilitating document management and collaboration within AIRA workflows.

- **Google Calendar API:** Allows users to create, update, and manage calendar events and schedules in Google Calendar, enabling automated scheduling and calendar management within AIRA workflows.

- **Gmail API:** Facilitates sending and receiving emails, managing email threads, and accessing email metadata, enabling communication and email automation within AIRA workflows.


## Integrate AIRA With Google Cloud

### Access Google Cloud Console:
- Go to the Google Cloud Console at https://console.cloud.google.com/.
- Log in to the Google Cloud Integration service using your Google login credentials.

### Create or Select a Project:
- Create a new one by clicking on the project dropdown menu at the top of the page and selecting "New Project."
- Enter the project name and location in the provided fields, then click on the "Create" button.
- If you have an existing project, select it from the project dropdown menu.

### Open Your Project:
- Once your project is created or selected, navigate to the project dashboard for app configuration.

### Enable Required APIs and Services:
- Navigate to the "APIs & Services" > "Library" section from the left-hand menu.
- Search for the APIs and services that you want to integrate with AIRA. For example, if you need to access Google Drive, enable the Google Drive API
- Click on the API you want to enable, then click the "Enable" button.

### OAuth consent Configuration 
- Navigate to the "OAuth consent screen" tab in the "API and Services" section.
- Choose the appropriate user type:
- Internal: Only available to users within your organisation. No need for app verification.
- External: Available to any test user with a Google Account. App starts in testing mode.
- Click on the continue.

### OAuth Consent Screen
- Fill in the required information
- App information:
  - App name: Name of the app requesting consent.
  - User support email: Contact email for users with consent inquiries.
  - App logo: Upload a logo for recognition on the consent screen.
  - Upload the logo file (max 1MB) and provide the app domain, home page link, privacy policy link, and terms of service link.
  - Register authorised domains for security purposes.
  - Enter developer contact information, including email addresses for notifications.
- Click "Save and continue."

### Scopes Configuration 
- Click on the "Add and Remove scope" button to add scopes in the scope section. Scopes define the permissions requested from users for accessing specific types of data.
- Click "Save and continue."

### Test User Configuration 
- In the next section, click on "Add user" to add test users. Only test users can access the app during testing mode.
- Set the publishing status to "Testing" and define the allowed user cap.
- Click "Save and continue."

### Summary
- Review the final summary before proceeding.

### Create Credential
- In the "APIs & Services" section of the Google Cloud Console, navigate to the "Credentials" tab.
- Click on the "Create Credentials" dropdown and select "OAuth client ID."
- Choose the appropriate application type based on your use case:
  - Web application: If you're building a web app accessed through a browser.
  - Mobile application: For iOS or Android apps.
  - Desktop app: If your app runs on desktop or laptop computers.
- Enter a name for your OAuth 2.0 client.
- Add the authorised JavaScript origins and redirect URIs:
  - Authorised JavaScript origins: URLs from which requests originate (e.g., http://localhost:3000).
  - Authorised redirect URIs: URLs where OAuth responses can be sent after user authorization (e.g., http://localhost:3000/auth/callback).
- Click the "Create" button to generate the OAuth client ID and client secret.


### Use the Client ID and Client Secret:
- Integrate the Client ID and Client Secret into AIRA’s authentication flow. This typically involves directing users to Google's OAuth 2.0 authentication endpoint with your Client ID and specifying the desired scopes.
- Navigate to the Administration section in AIRA.
- Click on the Integration Service option in the AIRA Administration panel.
- Find and select the Google Service option.
- Enter the Client ID and Client Secret obtained from the Google Cloud Console into the respective fields in the AIRA Google Integration settings.
- Provide additional information as needed:
  - ACCESS PERMISSIONS: Set to true to allow access permissions.
  - PROMPT: Specify the prompt type, such as "consent."
  - REDIRECT URL: Enter the redirect URL where users will be directed after authentication.
  - RESPONSE TYPE: Define the response type, usually "code" for OAuth 2.0.
  - STATE: Set any required state parameters.
  - URL: Enter the OAuth 2.0 authentication endpoint URL, typically https://accounts.google.com/o/oauth2/v2/auth.
- Click on the submit button to save the information and complete the integration.

----


<table align="right" border="0">
    <tr>
      <td align="center"><a href="https://aira.fr/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-previous.png" alt="Image 5" width="40" height="40"></a></td>
      <td align="center"><a href="https://aira.fr/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-next.png" alt="Image 5" width="40" height="40"></a></td>
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
