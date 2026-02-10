# ETL-Mini-Pipeline-Task-14
This project focuses on cleaning, processing, and analyzing retail transaction data using Python and SQLite. The main goal of this task was to perform data preprocessing, store the cleaned data in a database, and run SQL queries to extract meaningful business insights.

# Objective
 - Clean and preprocess raw retail data
 - Convert and format date columns properly
 - Handle invalid or missing values

# Tools & Technologies Used
 - Python (Pandas)
 - Jupyter Notebook

# Data Cleaning Steps
 - Loaded the dataset into Pandas.
 - Converted InvoiceDate to proper datetime format.
 - Removed rows with:
      - Missing CustomerID
      - Negative or zero Quantity
      - Negative or zero UnitPrice
 - Created a new column:
      - TotalSales = Quantity × UnitPrice
 - Exported the cleaned dataset to CSV

# Learning Outcomes
 - Data cleaning using Pandas
 - Working with datetime data
 - Creating calculated columns
 - Exporting processed data
