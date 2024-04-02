![blue 2](https://github.com/airacommunity/AIRA-User-Guide/assets/153823636/d8d04150-3b32-4b48-8485-07dc3c67fbaa)
# Report Creation in AIRA <img align="right" width="140" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/ARIA%20Logo%202.png?raw=true">

## Overview
AIRA reports are essential tools within the AIRA platform, providing visualized data insights for informed decision-making. Users can search previous reports or create new ones from scratch, defining chart details, configuring data sources, and customizing graph styles. These reports empower users with actionable insights derived from comprehensive data analysis.

<br>

> <img align="left" width="40" height="40" src="https://github.com/airacommunity/AIRA-User-Guide-Images/blob/main/icon-caution.jpg?raw=true"> Kindly note that the content provided is subject to regular updates. It may not reflect the final version. Your understanding is appreciated.

<br>

### Navigate to AIRA Reports

- Navigate to the left navigation bar in AIRA.
- Click on the "Report" section.
- Use the search bar at the top right corner to search for any previous reports.

### Create New Report

- Click on “Add New Dashboard."
- Provide a name and description for the report.
- Click "Submit."
- Provide a chart name and description.
- Click "Submit."

### Configure Data Source

- In the right-hand window, two options are available: "Data Source" and "Graph and Style."
- Choose "Data Source."
- Choose a data source using either the "Query Builder" or "Query Statement" options.

#### Query Builder

1. **Create or Select Data Set:**
- Select table users want to use to visualize.

2. **Join Tables:**
- Use the "Join" option to combine multiple tables.
- Provide the following information for each join:
  - Table
  - Join Type
  - Undefined Table
  - Table 2
  - Action (Join on key)

3. **Select Fields:**
- Choose the fields from the tables that you want to include in your report.

4. **Conditions:**
- Set conditions for your query using the "Condition" option.
- Include parameters such as:
  - Limit
  - Offset
  - Group By

5. **Order By:**
- Arrange your results using the "Order By" option.
- Specify fields and their sorting order (ASC or DESC).

6. **Where Clause:**
- Use the "Where" option to add conditions to your query based on specified fields and values.
  - Fields
  - Value
  - Action (Comparison action)

7. **Where Not Clause:**
- Similar to "Where," the "Where Not" option allows you to exclude results based on specified conditions.
  - Fields
  - Value
  - Action (Comparison action)

8. **Where In Clause:**
- Filter results based on inclusion in a specific column using the "Where In" option.
- Select the column you want to filter.
- With the help of the add button, users can include multiple filters.

9. **Where Not In Clause:**
- Exclude results based on exclusion from a specific column using the "Where Not In" option.
- Select the column you want to exclude.
- With the help of the add button, users can include multiple filters.

10. **Where Between Clause:**
- Specify a range for your results with the "Where Between" option.
- Choose the column and provide range values (from and to).

11. **Where Not Between Clause:**
- Exclude results falling within a specified range using the "Where Not Between" option.
- Choose the column and provide range values (from and to).

12. **Submit the Data source:**
- After selecting data click "Submit" to submit the data source.

#### Query Statement:
When using the Query Statement option in AIRA's Report section, you have the flexibility to write SQL queries to extract data based on your specific requirements. Here are examples of SQL queries for common data extraction scenarios:

  **Example :** Basic Data Retrieval
  
    ```
      SELECT * FROM Table_Name;
    ```
  **Submit the Data source:**
  - After wrting the SQL query, click "Submit" to submit the data source.


### Configure Graph and Style:
- User can Set up the style preferences and customize the chart style.
  - Setup : With this option user can select the graph type for the visualisation.
  - Customise : User can customise the chart style with this option.














