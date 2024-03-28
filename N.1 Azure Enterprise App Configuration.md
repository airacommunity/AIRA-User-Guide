![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# Azure Enterprise App Configuration <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">

## Overview

Effortlessly integrate AIRA applications with Azure through our comprehensive guide. Navigate Single Sign-On (SSO) setup using SAML, ensuring precision in configuration and credential management. Streamline authentication, enhance security, and optimise efficiency in your Azure environment with AIRA. 

<br>

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-caution.jpg?raw=true"> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

<br>

## Steps of Configuration 

### Step 1 : Login to Your Azure Account

- Begin the sign-on process by logging into your Azure account. If you don't have an account, you will need to create one. Ensure that you have the necessary credentials to access the Azure portal.

### Step 2: Access Entra ID from Azure Services

- Once logged in, navigate to the home page of Azure.
- Locate the "Azure Services" section on the home page.
- Select "Entra ID" from the Azure services section. This action will direct you to the Microsoft Entra ID Overview page.

### Step 3: Navigate to Enterprise Application

- In the Microsoft Entra ID Overview page, explore the left navigation bar.
- Scroll down until you find and select "Enterprise Application”. This will lead you to the Enterprise Application section.

### Step 4: Create a New Application

- Within the Enterprise Application section, click on the option "New Application" to create a new application.
- After clicking on "New Application", you will be prompted to start creating a new application.
- Click on the "Create Your Own Application" button to proceed with the application creation process.

### Step 5: Specify Application Name and Create

- After selecting "Create Your Own Application", a section titled "Create Your Own Application" will be presented.
- Within this section, enter the desired name for your application in the provided field.
- Click on the "Create" button to proceed with the application creation process.

### Step 6: Navigate to Application Overview

- Following the creation of your application, you will be redirected to the new application's overview page.
- To configure Single Sign-On settings, locate and select the "Single Sign-On" option from the left navigation bar.

### Step 7: Choose SAML Sign-On Method

- Within the Single Sign-On settings, a new page will open.
- Look for and select the "SAML" sign-on method to configure SAML-based authentication for your application.

### Step 8: Configure SAML-Based Sign-On

- After selecting the SAML Sign-On method, a new page titled "SAML-based Sign-on" will be displayed. This section is dedicated to configuring SAML set-up for your application.

### Step 9: Configure Basic SAML Settings

#### Edit Basic SAML Configuration

- Navigate to the "Basic SAML Configuration" section on the "SAML-based Sign-on" page.
- Click on the three dots, located on the right side of the section.
- Choose the "Edit" option to customise the basic SAML configuration.

#### Provide Identifier (Entity ID)

- In the "Edit Basic SAML Configuration" section, locate the field for "Identifier (Entity ID)."
- Access AIRA by logging in and navigating to the Admin section from the left navigation.
- Within the Admin section, click on "SAML Configuration" to reveal the Entity ID.
- Copy the Entity ID from AIRA and paste it into the "Add Identifier" field in the Basic SAML Configuration section.

#### Reply URL (Assertion Consumer Service URL)

In the "Edit Basic SAML Configuration" section, find the field for "Assertion Consumer Service URL."


- Login to AIRA, go to the Admin section, and then access the SAML Configuration.
- Retrieve the Assertion Consumer Service URL from AIRA.
- Copy the URL from AIRA and paste it into the "Add Reply URL" field in the Basic SAML Configuration section.
- Save all the Basic SAML Configuration.

### Step 10: Configure Attributes & Claims

- After configuring the Basic SAML settings, proceed to the "Attributes & Claims" section in the "SAML-based Sign-on" page.
- Within the "Attributes & Claims" section, click on the three dots located on the right side of the section.
- Select the "Edit" option to customise the attribute and claim settings.

#### Configure Unique User Identifier (Name ID)

- Once in the "Edit Attributes & Claims" section, search for "Unique User Identifier (Name ID)."
- Click on the value part of this section to open a new window for configuration.
- In the new window, locate the "Source Attribute" field.
- Enter "user.mail" as the source attribute. This ensures that the user's email address is used as the unique identifier.
- Save the changes to apply the configuration.

### Step 11: Configure SAML Certificates

- After configuring Attributes & Claims, proceed to the "SAML Certificates" section in the "SAML-based Sign-on" page.
- Within the "SAML Certificates" section, click on the three dots located on the right side.
- Choose the "Edit" option to customise the certificate settings.

#### Configure Signing Options

- After opening the edit tab, locate the "Signing options” is set to be “Sign SAML Assertion”.
- Verify that the "Signing Algorithm" is set to "SHA 256.".
- Save the section.

### Step 12: Configure Verification Certificates

- Within the "SAML Certificates" section, locate the "Verification Certificates" subsection.
- Click on the three dots on the right side of the "Verification Certificates" section.
- Choose the "Edit" option to customise the verification certificate settings.
- After opening the edit tab, check the option that says "Require Verification Certificates."
- In the same section, locate the "Upload" section or a field related to uploading the server public key.
- Upload the server public key file with a ".cer" extension.
- Save the section.

> Note : Command to generate private and public keys for SAML:
<br>

```
Code
openssl req -x509 -sha256 -nodes -days 365 -newkey rsa:4096 -keyout privateKey.key -out certificate.crt
```

<br>
### Step 13 : Open and Copy Public and Private Keys

- Open the generated public key (certificate.cer) and private key (privateKey.key) files using a text editor like Notepad or any other code editor.
- Copy the content of the public key file.
- Open the AIRA platform and navigate to the "Admin" section from the left navigation bar.
- Within the Admin section, select "SAML Configuration.
- Locate the field for "Public Key" and paste the content of the copied public key into this field.
- Now, go back to the text editor and copy the content of the private key file.
- Return to the AIRA "SAML Configuration" section.
- Find the field for "Private Key" and paste the content of the copied private key into this field.
- Save the changes to apply the public and private key configuration for SAML authentication in AIRA.

### Step 14: Download Certificate (Base64)

- Within the "SAML Certificates" section, find the "Download Certificate (Base64)" subsection.
- Click on the relevant option to download the certificate in Base64 format.
- Open the AIRA platform and select the "Admin" section from the left navigation bar.
- Within the Admin section, locate and select the "SAML Configuration" section.
- In the SAML Configuration section, find the area for uploading certificates.
- The Base64 certificate that you downloaded.

### Step 15: Retrieve Client ID and Tenant ID

In the AIRA Enterprise environment, navigate to the default directory from the top right corner.
Click on "App Registration" from the left navigation bar.
Choose the name of the application you generated.

#### Copy Client ID and Tenant ID

From the selected application, copy the "Client ID" and "Tenant ID" from the respective sections.

#### Paste IDs in AIRA Platform

Open the AIRA platform, select the "Admin" section from the left navigation bar.
In the Admin section, choose "SAML Configuration."
Paste the copied "Client ID" and "Tenant ID" in their respective sections.

#### Add New Secret Client

Click on "App Registration" from the left navigation bar.
Choose the name of the application you generated.
Click on the "Secrets" button in the App Registration section.
Click on the "New Client Secret" button.
Add a description for the new client secret.
Click on the "Add" button, and a new ID will be generated.

#### Copy Client Secret Value

- Copy the value of the newly generated client secret ID.

#### Paste Client Secret in AIRA Platform

- Open the AIRA platform, select the "Admin" section from the left navigation bar.
- In the Admin section, choose "SAML Configuration."
- Paste the copied client secret value in the respective section for client credentials.

Conslusion :
In summary, the guide outlines a comprehensive process for setting up Single Sign-On (SSO) using SAML for AIRA Enterprise Applications on the Azure portal. Users are guided through creating a new application, configuring SAML settings, managing attributes, and establishing SAML certificates for secure authentication. The emphasis is on accuracy in copying essential information. By following these steps, users can seamlessly integrate AIRA applications into their Azure environment, ensuring a secure and efficient Single Sign-On experience. It's essential to stay updated with platform changes and refer to official documentation for the latest information.

----


<table align="right" border="0">
    <tr>
        <td align="center" width = 200><a href="https://github.com/airacommunity/AIRA-User-Guide/blob/main/B.%20AIRA%20Components%20and%20System%20Requirements.md">NEXT</a></td>
    </tr>
</table>

<br>
<br>
<br>

<table border="0" align="center">
  <tr>
    <td align="center"><a href="https://aira.fr/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20web.png?raw=true" alt="Image 5" width="35" height="35"></a></td>
    <td><a href="https://www.linkedin.com/company/aira-rpa/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20linkedin.png?raw=true" alt="Image 1" width="30" height="30"></a></td>
    <td><a href="https://in.pinterest.com/connect_aira/"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20pinterest.png?raw=true" alt="Image 2" width="30" height="30"></a></td>
    <td><a href="https://www.youtube.com/channel/UCHHCcwQrx-_19sAhu-2R4ww"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20youtube.png?raw=true" alt="Image 3" width="30" height="30"></a></td>
    <td><a href="https://twitter.com/Aira_RPA"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20twitter.png?raw=true" alt="Image 4" width="30" height="30"></a></td>
    <td><a href="mailto:connect@aira.fr"><img src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon%20-%20gmail.png?raw=true" alt="Image 6" width="30" height="30"></a></td>
  </tr>
</table>


![Footer](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/6bb25f04-ad9c-476c-b653-c3c1dac1a868)

