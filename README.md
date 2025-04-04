# Azure Synapse Analytics Exploration Project

## Project Overview
This project highlights my hands-on experience with **Azure Synapse Analytics**, where I utilized a **serverless SQL pool** to query files in a data lake. My goal was to apply my SQL skills to analyze data stored in CSV, Parquet, and JSON formats. I set up an Azure Synapse Analytics workspace, uploaded files to a data lake, queried them, defined external data sources and tables for efficient access, and visualized the results. The exercise took approximately **40 minutes** and required an Azure subscription with administrative access.

## What I Did
1. **Created an Azure Synapse Analytics Workspace**
   * I used a PowerShell script in the Azure Portal to create a Synapse Analytics workspace and a linked Azure Data Lake Storage Gen2 account.
   * I uploaded sample sales data in CSV, JSON, and Parquet formats to the data lake.

2. **Explored Files in the Data Lake**
   * In Synapse Studio, I navigated to the **Data** tab to view the file structure in the data lake.
   * I observed that the **Sales** folder contained subfolders with CSV, JSON, and Parquet files.

3. **Queried CSV Files with SQL**
   * I used the OPENROWSET function to query CSV files.
   * I defined a schema with column names and data types, retrieving details like sales order numbers, customer information, and prices.

4. **Queried Parquet Files with SQL**
   * I queried Parquet files, leveraging their partitioning features to filter data by year (e.g., 2019 and 2020).

5. **Queried JSON Files with SQL**
   * I parsed JSON files using the JSON_VALUE function to extract fields like order numbers and customer names.

6. **Created an External Database and Table**
   * I created a new database and defined an external data source.
   * I set up external tables to make the data lake files queryable like regular database tables.

7. **Visualized Query Results**
   * I visualized query results in Synapse Studio using line and column charts.
   * For example, I plotted yearly revenue trends to analyze the data.

8. **Cleaned Up Resources**
   * To avoid unnecessary Azure costs, I deleted the resources I had created.

## What I Learned
* I learned how to query files in a data lake using a serverless SQL pool.
* I discovered how to define external data sources and tables for more organized and reusable data access.
* I realized I could visualize SQL query results to gain insights more easily.
* I gained an appreciation for the power of SQL in big data analytics and the flexibility of Azure Synapse Analytics.

## Contact Me
If you'd like to learn more about this project, feel free to reach out to me on LinkedIn(https://www.linkedin.com/in/eyilan/)
