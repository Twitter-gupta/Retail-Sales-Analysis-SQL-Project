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
<img width="1205" height="474" alt="image" src="https://github.com/user-attachments/assets/ff517d3f-6b88-4b00-8299-69173d9912b3" />

3. Data Analysis & Findings
The following SQL queries were developed to answer specific business questions:
3.1.   Write a SQL query to retrieve all columns for sales made on '2022-11-05:
<img width="1201" height="118" alt="image" src="https://github.com/user-attachments/assets/96b6f18b-3c05-45b1-a3d6-d390bc3bb11e" />

3.2. Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 4 in the month of Nov-2022:
<img width="1197" height="303" alt="image" src="https://github.com/user-attachments/assets/d783d92a-c4f2-4d82-8d29-1e2b3bd83b66" />

3.3. Write a SQL query to calculate the total sales (total_saleand total_order) for each category.:
<img width="1193" height="199" alt="image" src="https://github.com/user-attachments/assets/9ada6d72-e068-43e0-a595-69cecda4b7e4" />

3.4. Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.:
<img width="1206" height="150" alt="image" src="https://github.com/user-attachments/assets/34340048-d3b5-49c6-9c7b-7e1f47710542" />

3.5. Write a SQL query to find all transactions where the total_sale is greater than 1000.:
<img width="1198" height="94" alt="image" src="https://github.com/user-attachments/assets/47d45d7b-0aab-470b-9f74-97849be7e289" />

3.6. Write a SQL query to find the total number of transactions (transaction_id) made by each gender in each category.:
<img width="1201" height="325" alt="image" src="https://github.com/user-attachments/assets/4ab529bc-a8a5-44c3-affc-f617d7d6a90e" />

3.7. Write a SQL query to calculate the average sale for each month. Find out best selling month in each year:
<img width="1207" height="470" alt="image" src="https://github.com/user-attachments/assets/af5954b7-3b93-420a-b15e-1d2e7a542840" />

3.8. Write a SQL query to find the top 5 customers based on the highest total sales :
<img width="1209" height="226" alt="image" src="https://github.com/user-attachments/assets/ec0f8adb-eba9-4c97-88af-88bcfc0bfeb3" />

3.9. Write a SQL query to find the number of unique customers who purchased items from each category.:
<img width="1194" height="177" alt="image" src="https://github.com/user-attachments/assets/12f21fcd-eea5-47d3-bc62-58bcf7b05048" />

3.10. Write a SQL query to create each shift and number of orders (Example Morning <12, Afternoon Between 12 & 17, Evening >17):
<img width="1204" height="509" alt="image" src="https://github.com/user-attachments/assets/059bdaa5-217b-4fdc-9ec9-debeda372a75" />

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

















