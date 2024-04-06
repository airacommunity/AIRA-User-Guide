![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# AIRA Forms Activity <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">

The AIRA Form offers a user-friendly interface for manual data input in workflows, initiating case creation in the dedicated Case section. Cases allow structured data entry, with form elements as global variables usable across apps. After data entry, AIRA smoothly executes subsequent workflow steps, ensuring efficiency.

<br>

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/Icon-Warning.png?raw=true"> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

<br>

## To use AIRA Forms effectively, follow these steps:

### Navigate to AIRA Forms:

-   Go to the AIRA app section and locate the AIRA Forms option.
    
-   Click on it to access the forms functionality.
    

### Drag and Drop the Form:

-   Once in the AIRA Forms section, you'll see the option to create or select a form.
    


-   Simply drag and drop the AIRA Form component to the desired location where you want to integrate it into your workflow.
    


### Configure the Form:

-   Double-click on the form to configure it.
    
-   This action will open a form configuration window.
    

### Select Existing Form:

-   Choose the form you've previously created from the "Select Form" dropdown menu.
    


  

-   Define conditions for the execution of the form according to your workflow requirements. These conditions could determine when the form should be triggered or executed.
    

  

Variable Selection

-   Begin by typing "$$" to initiate the variable list display.
    
-   Review the list of available variables and select the one relevant to your condition.
    

Operator Selection

-   After selecting the variable, choose the appropriate operator for your condition.
    
-   Operators include "=", ">", "<", and more, depending on your specific requirement.
    

Value Input

-   Enter the value against which you want to evaluate the condition.
    
-   This value will be compared to the variable using the selected operator to determine the condition's outcome.
    

  

For Example : $$time$$ === "12"

  


-   Once conditions are applied, you have the option to either save or delete the form. If you're satisfied with the form and its conditions, proceed to save it for future workflow use.
    


-   After setting conditions and confirming your choices, click on the "Submit" button to save the form. This action ensures that the form is ready for use within your workflow.
    


### Create New Form

-   Click on the "Add new form" option at the top of the form configuration window.
    


  

-   A new window will open where you can provide a title and description for the form.
    


  

-   Click on the "Create form" button to proceed to the form creation window.
    


  

-   In the form creation window, you'll find various input components and custom options to design and customise your form according to your specific needs.
    


### Form Components and Usage

Access Form Components:

On the left-hand side of the interface, you'll find a toolbox containing various form components.
  

Select the Form Component:

Locate the Form component in the toolbox.

  

Drag and Drop:

Drag the Form component from the toolbox to the desired location on the form designer.

  

Configure Settings:

-   Once you drop the Form component onto the form designer, a settings window will appear.
    
-   This window allows you to set parameters for the Form component according to your requirements.
    

  

Adjust Parameters:

-   Inside the component settings, you can adjust various parameters.
    
-   Tooltips are provided in front of the setting options to assist you in understanding their functionalities.
    

### Form Components List

  

Basic Inputs:

  

-   Nested Form: Used to include multiple forms within a single form structure.
    
-   Dropdown: Presents a list of options for selection in a dropdown menu.
    
-   Hidden: A field that is part of the form but hidden from view.
    
-   Text Field: Allows users to input single-line text data.
    
-   Text Area: Allows users to input multiple lines of text.
    
-   Data Grid: Presents data in a tabular format for input or display.
    
-   Number: Accepts numeric input from users.
    
-   Password: Conceals user input for sensitive data.
    
-   Checkbox: Provides options for users to select one or multiple choices.
    
-   Select Box: Similar to a dropdown, allows selection from a list of options.
    
-   Select: Another form of selection input, often used for choosing from a list of options.
    
-   Radio: Presents options as radio buttons for single selection.
    
-   File: Allows users to upload files.
    
-   Button: Triggers specific actions when clicked, such as form submission.
    

  

Advance:

  

-   Email: Accepts input in the format of an email address.
    
-   URL: Accepts input in the format of a URL.
    
-   Phone Number: Accepts input in the format of a phone number.
    
-   Day: Allows users to select a specific date.
    
-   Time: Allows users to select a specific time.
    
-   Currency: Accepts input in the format of a currency.
    
-   Signature: Allows users to provide a digital signature.
    

  

Layout Components:

  

-   Grid: Organises form elements in a grid layout for better alignment.
    
-   Tab: Divides the form into tabs for organising and presenting information.
    
-   HTML Components: Allows the inclusion of custom HTML elements within the form.
    
-   Panel: Groups related form elements together within a panel for organisation.
    

  

Custom:

  

-   Data Picker: Allows users to select a specific date or time from a calendar.
    
-   Geo Location: Captures geographical location data.
    
-   QR Scanner: Enables scanning of QR codes to input data or trigger actions.
    

### Addition Settings

In the additional settings located at the top right corner of the form designer, you'll find the following options:

  


  

1. Preview: Allows you to preview the form layout and functionality before saving or deploying it. This feature helps ensure that the form appears and behaves as intended.

  

2. JavaScript: Enables you to apply special form functions using JavaScript. You can write custom JavaScript code to enhance the form's functionality or implement specific behaviours based on user interactions. To Know more about it, visit [AIRA form functions](https://docs.google.com/document/d/1jRi0jPBCZ1zNBLc6vMOi7_Yy-VCHGlWgA4eC1Np9rKM/edit?usp=drive_link).

  

3. Save: Saves the changes made to the form configuration. Clicking this option ensures that any modifications or updates to the form are retained.

  

4. Upload: Allows you to upload files or data to the form. This feature is useful for adding attachments or importing data into the form from external sources.

  

5. Download: Enables you to download files or data from the form. You can use this option to export form submissions, attachments, or any other relevant data for further analysis or storage.

  

These additional settings provide essential functionalities to manage and customise your form effectively, ensuring a seamless user experience and facilitating data collection and processing.

  

**Additional Options:**

Right-click on the app in the AIRA Designer workflow to access additional options:

- Unlink: Disconnect the app from any connected apps or tools in the workflow.

- Setting: Access and modify the settings of the app.

- Rename: Change the name of the apps for better organization.

- Trigger: Set triggers on the app to initiate actions based on specified conditions or events.

- Delete Module: Permanently delete the app from the workflow if it's no longer needed.

- Title : In the context you've provided, the title is a field or attribute used to assign a name or label to a form.

- Assignment Rule : An assignment rule, as described, is a mechanism used in case management systems to determine how tasks or cases are assigned to individuals or groups within an organisation. There are several types of assignment rules:

    -   Value-based Assignment: This type of rule assigns cases based on certain predefined variables or criteria.
    -   Self-service Assignment: cases are assigned to a designated group where members of that group can select and claim tasks themselves.
    -   Manual Assignment: This rule allows for manual assignment of cases by an administrator or supervisor. This could involve selecting a specific individual or team to handle a particular task or case.
    -   Report to Assignment: cases are assigned to the supervisor or manager of a particular individual. This can be useful for hierarchical structures where tasks need to be escalated to higher levels of authority.



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
