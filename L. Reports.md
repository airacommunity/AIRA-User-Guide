<h1><span style="color: #411d66;">Overview                                                    <img align="right" width="150" height="40" src="https://github.com/airacommunity/AIRA-Installation/assets/153823636/2aee8e84-f308-4494-a715-afd9421b606e">
</span></h1>


AIRA reports are essential tools within the AIRA platform, providing visualized data insights for informed decision-making. Users can search previous reports or create new ones from scratch, defining chart details, configuring data sources, and customizing graph styles. These reports empower users with actionable insights derived from comprehensive data analysis.
<blockquote class="is-warning">Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.</blockquote>
<h2 id="functionality-of-aira-report" class="toc-header">Functionality of AIRA Report</h2>
<h3 id="navigate-to-aira-reports" class="toc-header">Navigate to AIRA Reports</h3>
<ul>
 	<li>Navigate to the left navigation bar in AIRA.</li>
 	<li>Click on the "Report" section.</li>
 	<li>Use the search bar at the top right corner to search for any previous reports.</li>
</ul>
<h3 id="create-new-report" class="toc-header">Create New Report</h3>
<ul>
 	<li>Click on “Add New Dashboard."</li>
 	<li>Provide a name and description for the report.</li>
 	<li>Click "Submit."</li>
 	<li>New window will open, Provide chart name and description.</li>
 	<li>Click "Submit."</li>
</ul>
<h3 id="configure-data-source" class="toc-header">Configure Data Source</h3>
<ul>
 	<li>In the right-hand window, two options are available: "Data Source" and "Graph and Style."</li>
 	<li>Choose "Data Source."</li>
 	<li>Choose a data source using either the "Query Builder" or "Query Statement" options.</li>
</ul>
<h4 id="query-builder" class="toc-header">Query Builder</h4>
<ol>
 	<li><strong>Create or Select Data Set:</strong></li>
</ol>
<ul>
 	<li>Select table users want to use to visualize.</li>
</ul>
<ol start="2">
 	<li><strong>Join Tables:</strong></li>
</ol>
<ul>
 	<li>Use the "Join" option to combine multiple tables.</li>
 	<li>Provide the following information for each join:
<ul>
 	<li>Table</li>
 	<li>Join Type</li>
 	<li>Undefined Table</li>
 	<li>Table 2</li>
 	<li>Action (Join on key)</li>
 	<li>With the help of add button user can apply multiple join operation.</li>
</ul>
</li>
</ul>
<ol start="3">
 	<li><strong>Select Fields:</strong></li>
</ol>
<ul>
 	<li>Choose the fields from the tables that you want to include in your report.</li>
</ul>
<ol start="4">
 	<li><strong>Conditions:</strong></li>
</ol>
<ul>
 	<li>Set conditions for your query using the "Condition" option.</li>
 	<li>Include parameters such as:
<ul>
 	<li>Limit</li>
 	<li>Offset</li>
 	<li>Group By</li>
</ul>
</li>
</ul>
<ol start="5">
 	<li><strong>Order By:</strong></li>
</ol>
<ul>
 	<li>Arrange your results using the "Order By" option.</li>
 	<li>Specify fields and their sorting order (ASC or DESC).</li>
</ul>
<ol start="6">
 	<li><strong>Where Clause:</strong></li>
</ol>
<ul>
 	<li>Use the "Where" option to add conditions to your query based on specified fields and values.
<ul>
 	<li>Fields</li>
 	<li>Value</li>
 	<li>Action (Comparison action)</li>
</ul>
</li>
</ul>
<ol start="7">
 	<li><strong>Where Not Clause:</strong></li>
</ol>
<ul>
 	<li>Similar to "Where," the "Where Not" option allows you to exclude results based on specified conditions.
<ul>
 	<li>Fields</li>
 	<li>Value</li>
 	<li>Action (Comparison action)</li>
</ul>
</li>
</ul>
<ol start="8">
 	<li><strong>Where In Clause:</strong></li>
</ol>
<ul>
 	<li>Filter results based on inclusion in a specific column using the "Where In" option.</li>
 	<li>Select the column you want to filter.</li>
 	<li>With the help of the add button, users can include multiple filters.</li>
</ul>
<ol start="9">
 	<li><strong>Where Not In Clause:</strong></li>
</ol>
<ul>
 	<li>Exclude results based on exclusion from a specific column using the "Where Not In" option.</li>
 	<li>Select the column you want to exclude.</li>
 	<li>With the help of the add button, users can include multiple filters.</li>
</ul>
<ol start="10">
 	<li><strong>Where Between Clause:</strong></li>
</ol>
<ul>
 	<li>Specify a range for your results with the "Where Between" option.</li>
 	<li>Choose the column and provide range values (from and to).</li>
</ul>
<ol start="11">
 	<li><strong>Where Not Between Clause:</strong></li>
</ol>
<ul>
 	<li>Exclude results falling within a specified range using the "Where Not Between" option.</li>
 	<li>Choose the column and provide range values (from and to).</li>
</ul>
<ol start="12">
 	<li><strong>Submit the Data source:</strong></li>
</ol>
<ul>
 	<li>After selecting data click "Submit" to submit the data source.</li>
</ul>
<h4 id="query-statement" class="toc-header">Query Statement:</h4>
When using the Query Statement option in AIRA's Report section, you have the flexibility to write SQL queries to extract data based on your specific requirements. Here are examples of SQL queries for common data extraction scenarios:

<strong>Example :</strong> Basic Data Retrieval

&nbsp;
<div class="code-toolbar">
<pre class="prismjs line-numbers language-js"><code class="language-js"># For Current Example

select * from table ;</code></pre>
</div>
&nbsp;

Submit the Data source:
<ul>
 	<li>After wrting the SQL query, click "Submit" to submit the data source.</li>
</ul>
<h3 id="configure-graph-and-style" class="toc-header">Configure Graph and Style:</h3>
<ul>
 	<li>User can Set up the style preferences and customize the chart style.
<ul>
 	<li>Setup : With this option user can select the graph type for the visualisation.
<ul>
 	<li>Basic Bar Chart</li>
 	<li>Grouped Bar Chart</li>
 	<li>Stacked Bar Chart</li>
 	<li>Basic Line Chart</li>
 	<li>Steped Line Chart</li>
 	<li>Basic Area Chart</li>
 	<li>Spline Area Chart</li>
 	<li>Table Chart</li>
</ul>
</li>
 	<li>Customise : User can customise the chart style with this option.</li>
</ul>
</li>
</ul>
&nbsp;

----
![Footer](https://github.com/airacommunity/AIRA-Installation/assets/153823636/f78c5168-fae6-4a12-a01d-8e98fe7d7ae2)
