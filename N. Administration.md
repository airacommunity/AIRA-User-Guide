![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# Administration <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">

## Overview
The Administration section of AIRA serves as a central hub for organizing and managing the application's key functionalities and settings. From user management to system configuration, this section provides users with intuitive tools to streamline organizational tasks and ensure smooth operation of the AIRA platform. With features like user management, document storage, integration options, and system configuration settings, AIRA's Administration empowers users to efficiently control and customize their automation workflows to meet their specific needs.

<br>

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-caution.jpg?raw=true"> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

<br>

## Guide to utilize administrative functions

### Navigate to Administration
- Scroll down the left navigation panel of the AIRA interface.
- Click on the "Administration" option.

**Functions In Administration**

<table border="0">
  <tr>
    <td width=350>Organisation</td>
    <td width=350>SAML Configuration</td>
    <td width=350>Document Management</td>
    <td width=350>Licenses</td>
  </tr>
  <tr>
    <td width=350>Integration Service</td>
    <td width=350>System Configuration</td>
    <td width=350>Master Data Management</td>
    <td width=350></td>
  </tr>
</table>

### Organization

The Organization section provides detailed information about users, groups, roles, and departments within the organization that utilize Aira. Let's dive into each aspect individually.

#### 1. Role

- **View and Manage Roles:**
  - Displayed information includes Name, Description, Creation Date, Status, and Action.
  - By clicking on "Action," a window opens allowing for the modification of various role details.
  
- **Editing Role Details:**
  - Users can edit Title, Name, Description, and set permissions.
  - Update permissions accessible to the role.
  - Upon completion of editing, users can save changes by clicking "Submit."

- **Search Functionality:**
  - A search bar positioned above the role table facilitates role search by name.

- **Adding New Roles:**
  - Adjacent to the search bar, there's an "Add Role" button.
  - Upon clicking, users are prompted to:
    - Fill in details such as Title, Name, and Description.
    - Define permissions accessible to the role.
    - After configuring permissions, users can save the new role by clicking "Submit."

#### 2. User
The "User Section" provides a comprehensive view of all users utilizing aira within the organization.

- **View and Manage User:**
  - Displayed information includes Name, Designation, Email, Role, Reports To, Status, and Action.
  - By clicking on "Action," a window opens allowing for the modification of various user details.
  - A delete button is next to action to delete any user.
  
- **Editing User Details:**
  - Users can edit Editable information includes First Name, Last Name, Designation, Email, Contact number, Organization, Address, Country, State, Password, Language, Time Zone, Reports to, and Roles.
  - Before edit or add user group, roles availabe in aira organization is mandatory.
  - Upon completion of editing, users can save changes by clicking "Submit."

- **Search Functionality:**
  - A search bar positioned above the user table facilitates user search by name.

- **Adding New User:**
  - Adjacent to the search bar, there's an "Add User" button.
  - Upon clicking, users are prompted to:
    - Fill in details such as First Name, Last Name, Designation, Email, Contact number, Organization, Address, Country, State, Password, Language, Time Zone, Reports to, and Roles.
    - Save the new user by clicking "Submit."

#### 3. Group

The "Group Section" provides a comprehensive view of all group utilizing aira within the organization.

- **View and Manage Group:**
  - Displayed information includes Name, Created By, Created At, Status, Action.
  - By clicking on "Action," a window opens allowing for the modification of various group details.

- **Editing Group Detail:**
  - Users can edit Editable information includes Name, Description, Select User by dropdown option.
  - Before edit or add new group, user availabe in aira organization is mandatory.
  - Upon completion of editing, users can save changes by clicking "Submit."

- **Search Functionality:**
  - A search bar positioned above the group table facilitates group search by name.

- **Adding New Group:**
  - Adjacent to the search bar, there's an "Add Group" button.
  - Upon clicking, users are prompted to:
    - Fill in details such as Name, Description, Select User by dropdown option.
    - Save the new group by clicking "Submit."

#### 4. Department
The "Department Section" provides a comprehensive view of all department and its manager name utilizing aira within the organization.

- **View and Manage Department:**
  - Displayed information includes Name, Manager, Created At, Status, Action.
  - By clicking on "Action," a window opens allowing for the modification of various Department detail details.

- **Editing Department Detail:**
  - Users can edit Editable information includes Name and drop down option for manager selection.
  - Before edit or add new Department, user availabe in aira organization is mandatory.
  - Upon completion of editing, users can save changes by clicking "Submit."

- **Search Functionality:**
  - A search bar positioned above the department table facilitates department search by name.
 
- **Adding New Department:**
  - Adjacent to the search bar, there's an "Add Department" button.
  - Upon clicking, users are prompted to:
    - Fill in details such as Name and select manager with the help of drop down option.
    - Save the new group by clicking "Submit."
   
### SAML Configuration

SAML (Security Assertion Markup Language) configuration in AIRA enables smooth and secure integration with Azure. We have to provide all the information for the SAML configuration if you want to know more about how to configure SAML with aira visit [azure enterprise application login](url).

### Document Management

Document management in AIRA provides a centralised repository for storing and organising files related to workflows and system assets. 

AIRA's Document Management is organised into a storage folder, and within it, you will find default directories for assets, input files, and output files. These directories help categorise and manage various types of documents efficiently.

**Default Directories**
On the left hand side of the document management section directories section is available, above the directories section there is a search bar available on it, which is used to search directory in the system. On the right side of the directories section, the documents section is available which shows all documents available in the specific directory. There are three default directories available in AIRA.

- **Asset Folder:** Contains logos and default assets used within AIRA.
- **Input Folder:** Houses certificates and files uploaded during workflow execution.
- **Output Folder:** Stores output files generated by workflows.

**Document Management: Download and Delete**
- Next to each document, there's a download button for users to download the file.
- Adjacent to the download button, users can find a delete button to remove the document.

**Search Functionality**
- On the right side of the Document Management window, there is a search bar. This feature allows users to quickly locate specific documents within the selected directory.

**Uploading Files**
- Click on the "Upload" button next to the left search bar.
- Drag and drop files from your local system into the designated area, or alternatively, upload files using the folder path.

### Licenses

The License Management section in AIRA provides crucial information about your AIRA licence, ensuring you have a clear understanding of its status and usage. Here's a detailed guide on how to navigate and utilise the License Management feature:

**Licence Overview**
The License section encompasses essential details about your AIRA licence. This information includes:

- **Issued To:** Indicates the entity or user to whom the licence is issued.
- **Issued Date:** Represents the date on which the licence was initially issued.
- **Activation Date:** Marks the date when the licence was activated for use.
- **Remaining Days:** Displays the number of days remaining until the licence expires.
- **Users:** Specifies the number of users covered by the licence.
- **Transactions:** Provides information on the total number of transactions allowed under the licence.

**Transaction Graph** : On the right-hand side of the License Management section, a transaction graph is featured. This graph visually represents the total number of transactions based on either the year or month selection. This graphical representation offers a quick overview of transaction trends over time.

### Integration Service
AIRA Integration Service enables seamless connectivity with external platforms, empowering users to incorporate the functionalities of various third-party services into automation workflows. Through integration, users can use the capabilities of external platforms within the AIRA ecosystem, enhancing productivity and efficiency.

**Integration Activation:**
- Provide a simple switch to start the integration process.
- Note : Google and MailChimp integrations require configuration before activation.

<table border="0">
  <tr>
    <th colspan="4">Integration Service</th>
  </tr>
  <tr>
    <td width=300>Azure</td>
    <td width=300>Google</td>
    <td width=300>Mailchimp</td>
    <td width=300>AWS</td>
  </tr>
  <tr>
    <td>MySQL</td>
    <td>Oracle Fusion Cloud ERP</td>
    <td>PostgreSQL</td>
    <td>Salesforce</td>
  </tr>
  <tr>
    <td>SAP BAPI</td>
    <td>SFTP</td>
    <td>EMAIL</td>
    <td></td>
  </tr>
</table>

**Google Integration Configuration**

Google Integration with AIRA enables users to integrate Google's suite of productivity tools and services seamlessly into their automation workflows. By connecting with Google, users can access services such as Google Drive, Google Sheets, Gmail, Google Calendar, and more directly within the AIRA platform. This integration streamlines collaboration, data management, communication, and task automation, allowing users to leverage Google's powerful tools to enhance productivity and efficiency.

To configure the integration with the platform, detailed [documentation](url) is available, providing step-by-step instructions on how to set up the integration effectively. This document outlines the necessary configurations, settings, and authentication processes required to establish a seamless connection between AIRA and the respective platform.

**Mailchimp Integration Configuration**

Mailchimp Integration with AIRA facilitates seamless integration of Mailchimp's email marketing platform into automation workflows. By connecting with Mailchimp, users can automate email campaigns, manage subscriber lists, track engagement metrics, and more directly within the AIRA platform. This integration simplifies email marketing processes, enhances campaign management, and improves audience targeting, enabling users to leverage Mailchimp's robust features to drive effective marketing campaigns and achieve their business goals.

To configure the integration with the platform, detailed [documentation](url) is available, providing step-by-step instructions on how to set up the integration effectively. This document outlines the necessary configurations, settings, and authentication processes required to establish a seamless connection between AIRA and the respective platform.

### System Configuration

The System Configuration section in AIRA provides a comprehensive view of both system and personal information. This section is essential for understanding the underlying infrastructure of the AIRA platform and customising personal details. Here's a detailed guide on how to navigate and utilise the System Configuration feature:
System Information

**System Information**

 <table border="0" cellspacing="0" cellpadding="8">
        <tr>
            <th>Category</th>
            <th>Information</th>
        </tr>
        <tr>
            <td>Basic Info</td>
            <td>
                <strong>Platform:</strong> Indicates the underlying operating system of the AIRA platform, which is Linux.<br>
                <strong>Arch:</strong> Specifies the system architecture, which is x64.<br>
                <strong>Network Interfaces:</strong> Displays the IP address (e.g., 139.99.46.115) used by the platform.<br>
                <strong>Web Server:</strong> Provides details about the web server being utilised, including its version (e.g., nginx/1.24.0).<br>
                <strong>Host Name:</strong> Represents the host name of the system (e.g., vps-6f6e9a73.vps.ovh.ca).
            </td>
        </tr>
        <tr>
            <td>Versions</td>
            <td>
                <strong>Version:</strong> Displays information about the current version of the system.<br>
                <strong>Mysql Version:</strong> Specifies the version of MySQL being used (e.g., 5.7.41).<br>
                <strong>Node Version:</strong> Indicates the version of Node.js installed (e.g., v16.20.2).<br>
                <strong>OS Version:</strong> Provides details about the operating system version (e.g., centos-release-7-9.2009.1.el7.centos.x86_64).
            </td>
        </tr>
        <tr>
            <td>CPU Info</td>
            <td>
                <strong>Model:</strong> Specifies the model of the CPU (e.g., Intel Core Processor - Haswell, no TSX).<br>
                <strong>Speed:</strong> Indicates the speed of the CPU (e.g., 2399).
            </td>
        </tr>
    </table>

**Personalisation**

 <table border="0" cellspacing="0" cellpadding="8">
        <tr>
            <th width=300>Option</th>
            <th width=1800>Description</th>
        </tr>
        <tr>
            <td>Title</td>
            <td>Allows users to set a personalised title.</td>
        </tr>
        <tr>
            <td>Logo Light</td>
            <td>Enables customization of the light version of the logo.</td>
        </tr>
        <tr>
            <td>Logo Dark</td>
            <td>Allows customization of the dark version of the logo.</td>
        </tr>
        <tr>
            <td>Favicon</td>
            <td>Provides an option to set a personalised favicon.</td>
        </tr>
        <tr>
            <td>Monogram</td>
            <td>Allows users to set a personalised monogram.</td>
        </tr>
    </table>

You can Edit the Title, Logo Light, Logo Dark, Favicon, and Monogram based on preferences and save the changes.

### Master Data Management

Master Data Management (MDM) in AIRA allows users to create and manage tables that can be utilised in report creation. The MDM section consists of two main options: Tables and Report Tables. Here's a step-by-step guide on how to navigate and use these features:

**Table Section**

The Table Section in Aira serves the purpose of both data creation and upload. These tables play a pivotal role in generating reports and facilitating automation processes.

- Navigate to Administration and select "Master Data Management."
- Upon entering the Tables section, various tables are displayed, showcasing pertinent information such as Table Name, Total Records, Created at, and available Actions.
- Two primary actions are available: Delete and View.
  - **Delete:** Utilized for removing a table.
  - **View:** Allows users to inspect the table's data.
- Utilize the search bar positioned at the top right to swiftly locate specific tables.
- Next to the search bar, users can find the "Upload Table" option.
- Tables in PMT format can be conveniently uploaded via drag-and-drop or browsing.

**Adding a New Table**

- Click on the "Add Table" button to initiate the process.
- Provide essential details such as Table Name and Description.
- Utilize the "Add Column" option to specify column details including Column Name, Column Label, Data Type, Size, Null, Auto Increment, Index, Unique, Primary Key, Foreign Key, Reference Table, Reference Column, and available Actions.
- Upon defining all columns, click "Create" to finalize the table creation.

**Viewing Table Details**

- Click on the View button to access detailed information about the table.
- A search bar is available above the detailed table for streamlined data exploration.
- Import and export CSV options are positioned adjacent to the search bar, facilitating data management.
- The View Schema button, located next to the Import/Export options, provides insights into the table's schema.

**Report Table**
The "Report table" section facilitates the creation of table-formatted representations from workflow variables.

**1. Viewing and Deleting Existing Tables:**

- Navigate to the Report Tables section.
- Existing tables will be displayed.
- To view a table, click on "View Table." This allows users to see complete information about each report table.
- To delete a table, click on "Delete Table." This action removes the complete table and its associated data.

**Searching for Specific Report Tables:**
Utilize the search bar provided to find specific report tables quickly.

**Adding a New Report Table:** 
- Click on the "Add Table" button.
- In the new interface, provide a title for the table.
- Specify the following:
  - Jobs (Workflows)
  - Variable Type (Global or Grid)
  - If Grid is selected, choose Grid Type
  - Variable.
- Under the "Variable" section, define the following:
  - Primary Key
  - Foreign Key
  - Reference Table
  - Reference Column
  - Action (For deleting Variable).
- Click "Create" to finalize the report table creation.

<br>

As we conclude the Administration section, envision the impact of proficient administration in fostering excellence and ensuring the sustained success of your AIRA initiatives.

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
