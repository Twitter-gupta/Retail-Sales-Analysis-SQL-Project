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
<img width="1201" height="142" alt="image" src="https://github.com/user-attachments/assets/b187874b-ac79-45b1-911f-3a14f83f831a" />

3.d. Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.:
<img width="1199" height="83" alt="image" src="https://github.com/user-attachments/assets/0019499e-63dd-4559-be86-9d0debe9b680" />

3.e. Write a SQL query to find all transactions where the total_sale is greater than 1000.:
<img width="1198" height="325" alt="image" src="https://github.com/user-attachments/assets/0f2a539d-9c57-4e09-ae82-f9fb3061b07e" />

3.f. Write a SQL query to find the total number of transactions (transaction_id) made by each gender in each category.:
<img width="1201" height="486" alt="image" src="https://github.com/user-attachments/assets/06b9c28f-9c66-4692-9b39-7e8cf0d42440" />

3.g. Write a SQL query to calculate the average sale for each month. Find out best selling month in each year:
<img width="1207" height="234" alt="image" src="https://github.com/user-attachments/assets/b0d52c60-8cfd-4d19-859a-253eee72b7dc" />

3.h. Write a SQL query to find the top 5 customers based on the highest total sales :
<img width="1199" height="178" alt="image" src="https://github.com/user-attachments/assets/e4ef638d-1605-4734-86f5-9772470cad8f" />

3.i. Write a SQL query to find the number of unique customers who purchased items from each category.:
<img width="1197" height="524" alt="image" src="https://github.com/user-attachments/assets/254b84fa-6c26-465e-85f7-addadfe35d27" />

3.j. Write a SQL query to create each shift and number of orders (Example Morning <12, Afternoon Between 12 & 17, Evening >17):
<img width="1298" height="11" alt="image" src="https://github.com/user-attachments/assets/2423abcd-1bf5-45ae-81b3-48dae528ab32" />

Findings - 
Customer Demographics: The dataset includes customers from various age groups, with sales distributed across different categories such as Clothing and Beauty.
High-Value Transactions: Several transactions had a total sale amount greater than 1000, indicating premium purchases.
Sales Trends: Monthly analysis shows variations in sales, helping identify peak seasons.
Customer Insights: The analysis identifies the top-spending customers and the most popular product categories.

Reports - 
Sales Summary: A detailed report summarizing total sales, customer demographics, and category performance.
Trend Analysis: Insights into sales trends across different months and shifts.
Customer Insights: Reports on top customers and unique customer counts per category.

Conclusion - 
This project serves as a comprehensive introduction to SQL for data analysts, covering database setup, data cleaning, exploratory data analysis, and business-driven SQL queries. The findings from this project can help drive business decisions by understanding sales patterns, customer behavior, and product performance.

















