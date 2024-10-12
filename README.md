# Sensor Data Engineering using PySpark and Azure Databricks

This project showcases data engineering techniques using PySpark on Azure Databricks to process and analyze sensor data. The dataset consists of two key files: an **hourly sensor counts dataset** and a **sensor location dataset**.

## Project Workflow
1. **Data Ingestion**: Load datasets from Azure Blob Storage into Databricks using PySpark.
2. **Data Cleaning**: Handle missing values, remove duplicates, and standardize data formats.
3. **Data Transformation**: Join the sensor counts with sensor locations, aggregate the hourly counts, and create relevant features.
4. **Data Analysis**: Perform exploratory data analysis (EDA) to understand sensor usage trends.
5. **Data Storage**: Store the cleaned and processed data back to Azure Blob Storage for further analysis or reporting.

## Requirements
- Azure Databricks
- PySpark
- Azure Blob Storage

This project demonstrates how to leverage Azure Databricks for large-scale sensor data engineering using PySpark.

Feel free to explore and customize the code based on your use case!
