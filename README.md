# sales_insights-using-power-Bi
Objective:
The objective of this project is to design a robust sales database, perform structured queries, and create an interactive dashboard that provides meaningful insights into customer behavior, sales trends, and business performance.

Project Overview:
This project integrates MySQL for backend database management and Power BI for front-end visualization. The sales dataset contains information about customers, time dimensions, and transactions. By analyzing this data, the project aims to provide a comprehensive view of sales performance across different customer segments and time periods.

Modules / Components:
Database Creation (MySQL):
Built a database named sales.
Created tables such as:
Customers: Stores customer details like customer_code, customer_name, and customer_type (e.g., Brick & Mortar, E-Commerce).
Date Dimension: Contains calendar attributes (date, year, month_name, etc.) to support time-series analysis.
Transactions / Sales Records (implied in dataset): Records of sales linked with customers and dates.

Data Management:
Imported raw sales data into MySQL.
Applied normalization for efficient data storage.
Used SQL queries for data cleaning, aggregation, and analysis (e.g., total sales by customer type, monthly revenue trends).

Data Visualization (Power BI):
Connected Power BI with the MySQL database.
Designed dashboards with the following insights:
Sales Trends: Revenue patterns over days, months, and years.
Customer Insights: Performance comparison between Brick & Mortar and E-Commerce customers.
Top Customers & Products: Ranking of highest revenue contributors.
KPIs: Key metrics such as total revenue, profit margin, and growth percentage.

Technologies Used:
Database: MySQL (SQL queries, schema design, data storage)
Visualization Tool: Microsoft Power BI (dashboards, charts, KPIs)
Language: SQL
Data Type: Sales and customer records

Key Outcomes:
Built a centralized sales database for structured data analysis.
Created interactive dashboards for management decision-making.
Provided actionable insights such as:
Which customer type contributes more revenue.
Seasonal and monthly sales performance.
Identification of top-performing customers.
Applications:
Helps businesses track sales performance in real-time.
Supports decision-making for marketing, supply chain, and inventory planning.
Can be extended for forecasting future sales trends using advanced analytics.
