<h1><span style="color: #411d66;">Overview                                                    <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e">
</span></h1>


Cases in AIRA are integral components of workflows, representing stages where human interaction or decision-making is required. But to understand “Cases” first we have to understand the “Forms” app activity. To learn about AIRA forms, visit the <a class="is-external-link" href="http://wiki.aira.technology:8000/en/user-guide/aira-form">AIRA Form</a> section.

Forms in AIRA workflows play a crucial role in facilitating human-centric activities and data collection within processes.
<ul>
 	<li><strong>Human Activity Focus:</strong> Form app is designed to cater to human-centric tasks within workflows.</li>
 	<li><strong>Data Collection Hub:</strong> This app serves as a central hub for collecting and processing human-inputted data.</li>
</ul>
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h2 id="relationship-between-form-and-workflow" class="toc-header">Relationship Between Form and Workflow</h2>
When the Form module is incorporated into a workflow, it automatically triggers the creation of a corresponding case. Cases essentially function as sub-parts of the Form module, dedicated to capturing and processing data specific to the form. The data entered within the case corresponds to the respective form fields established within the workflow, establishing a smooth connection between human-driven interactions and the structured data collection process. This integral relationship ensures that the workflow progresses efficiently, using the captured data for further processing and automation.
<h2 id="assignment-rules-and-case-types" class="toc-header">Assignment Rules and Case Types:</h2>
<ul>
 	<li><strong>Workflow Integration:</strong> Cases are generated when “Form” are included in workflow, and assignment rules play a pivotal role in determining the case type.</li>
 	<li><strong>Dynamic Categorization:</strong> Based on assignment rules, cases are dynamically categorized into Inbox, Unassigned, Participated, and more.</li>
</ul>
<h2 id="cases-user-interface" class="toc-header">Cases User Interface</h2>
The user interface of Aira Cases features five primary options: "Start Execution," "Inbox Section," "Participated," "Unassigned," and "Advanced Search."
<h3 id="start-execution" class="toc-header">Start Execution</h3>
This section facilitates users to continuously execute a specific case and fill in the required data.
<ul>
 	<li><strong>Select Case Action:</strong> Click on the specific case action arrow to initiate.</li>
 	<li><strong>Fill Data:</strong> Input the necessary data into the designated fields.</li>
 	<li><strong>Submit:</strong> Click on the submit button to save the entered data.</li>
 	<li><strong>Case Search:</strong> Above the "Start Execution" section table, a search bar is provided. Utilize the search bar by entering the job name to locate any specific case efficiently.</li>
</ul>
<h3 id="inbox" class="toc-header">Inbox</h3>
When the form's assignment rule is set to manual assignment to a specific person, the case is directed to the Inbox of that individual.

<strong>Example:</strong> A workflow assigns a form to "vishwajeet.aira" via manual assignment rule, the case will appear in the Inbox of the designated user.

Alternatively, if the assignment rule is set to "reports to" a specific person, the case is directed to the inbox of the reporting manager.

<strong>Example:</strong> If the assignment rule is "reports to vishwajeet.aira," the case is forwarded to the inbox of the manager of "vishwajeet.aia”.
<ul>
 	<li><strong>Select Case:</strong> Click on the specific case to open it.</li>
 	<li><strong>Fill Data:</strong> Input the required information into the relevant fields.</li>
 	<li><strong>Submit:</strong> Click on the submit button to save the entered data.</li>
 	<li><strong>Case Search:</strong> Above the Inbox section table, a search bar is provided. Utilize the search bar by entering the Case No., Case Title, or Job Name to quickly locate any specific case.</li>
</ul>
<h3 id="participated" class="toc-header">Participated</h3>
After successfully completing the case-related tasks, cases are moved to the Participated section for reference and record.
In the Participated section, there's a table displaying cases, including their Case No., Case Title, Job Name, and Status.
<ul>
 	<li><strong>Search Cases:</strong> Utilize the search bar to find specific cases by entering their Case No., Case Title, or Job Name.</li>
 	<li><strong>Filter by Status:</strong> Adjacent to the search bar, a status button is available. Click on this button to filter the table by status. It enables users to view all statuses, open cases, or closed cases.</li>
</ul>
<h3 id="unassigned" class="toc-header">Unassigned</h3>
In the Unassigned section, cases are directed when the assignment rule is set to self-service with a selected group, or if no assignment rule is specified. Here, any person within the selected group can accept the case, moving it to their inbox for completion.
<ul>
 	<li><strong>Select Case:</strong> Click on the specific case to open it.</li>
 	<li><strong>Fill Data:</strong> Input the necessary data into the relevant fields.</li>
 	<li><strong>Submit:</strong> Click on the submit button to save the entered data.</li>
 	<li><strong>Case Search</strong>: Above the Unassigned section table, a search bar is provided. Utilise the search bar by entering the Case No., Case Title, or Job Name to quickly locate any specific case.</li>
</ul>
<h3 id="advanced-search" class="toc-header">Advanced Search</h3>
The Advanced Search section offers a comprehensive approach to accessing detailed case information, thereby facilitating efficient case management. It includes the following fields (Case No., Case Title, Job Name, Status, Start Date, Due Date)
<ul>
 	<li><strong>Search Cases:</strong> Utilize the Advanced Search table to input specific criteria such as Case No., Case Title, Job Name, Status, Start Date, or Due Date to find relevant cases.</li>
 	<li><strong>View Case History:</strong> Clicking on any case within the Advanced Search results will display a history table specific to that case, providing a detailed record of its activities and progress.</li>
 	<li><strong>Backend Code:</strong> In history table click on the specific case to see the the backend code of the case.</li>
 	<li><strong>Filter by Status:</strong> Adjacent to the search bar, a status button is available. Click on this button to filter the table by status. It enables users to view all statuses, open cases, or closed cases.</li>
</ul>
&nbsp;

----
![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
