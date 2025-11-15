# Retail-Sales-Analysis-SQL-Project
This project utilizes SQL to perform a comprehensive analysis of a retail company's sales data. The primary objective is to extract actionable insights, identify sales trends, evaluate product performance, and inform data-driven business strategies. 

Objectives
1. Set up a retail sales database: Create and populate a retail sales database with the provided sales data.
2. Data Cleaning: Identify and remove any records with missing or null values.
3. Exploratory Data Analysis (EDA): Perform basic exploratory data analysis to understand the dataset.
4. Business Analysis: Use SQL to answer specific business questions and derive insights from the sales data.

Project Structure
1. Database Setup
Database Creation: The project starts by creating a database named p1_retail_db.
Table Creation: A table named retail_sales is created to store the sales data. The table structure includes columns for transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.

<img width="1203" height="496" alt="image" src="https://github.com/user-attachments/assets/29c65560-b2ec-465b-a5d2-c4e0d90ffe16" />

2. Data Exploration & Cleaning
  Record Count: Determine the total number of records in the dataset.
  Customer Count: Find out how many unique customers are in the dataset.
  Category Count: Identify all unique product categories in the dataset.
  Null Value Check: Check for any null values in the dataset and delete records with missing data.

<img width="1186" height="104" alt="image" src="https://github.com/user-attachments/assets/cc573114-6c2d-4536-bc65-7126abbbafde" />

3. Data Analysis & Findings
The following SQL queries were developed to answer specific business questions:
3.a.   Write a SQL query to retrieve all columns for sales made on '2022-11-05:

<img width="1203" height="295" alt="image" src="https://github.com/user-attachments/assets/2da6e1cd-dba1-4398-9c0f-dc9939bb4b8c" />

3.b. Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 4 in the month of Nov-2022:
<img width="1185" height="203" alt="image" src="https://github.com/user-attachments/assets/843cb839-57d4-4e3e-bdf5-6a8389e47535" />

3.c. Write a SQL query to calculate the total sales (total_saleand total_order) for each category.:
![Uploading image.png…]()








