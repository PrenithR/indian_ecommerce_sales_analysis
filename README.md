Indian E-Commerce Sales Analysis
Project Overview

This project analyzes an Indian e-commerce sales dataset to identify trends in sales, profitability, customer purchasing behavior, delivery performance, and sales target achievement. The project combines Python (Data Cleaning & EDA), SQL, Excel, and Power BI to transform raw transactional data into actionable business insights through interactive dashboards.

Objectives
Analyze sales and profit performance across different product categories.
Identify high-performing and underperforming categories.
Evaluate courier partner performance and delivery status.
Compare actual sales against monthly sales targets.
Build interactive dashboards to support business decision-making.

Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)
SQL
Microsoft Excel
Power BI
DAX

Project Workflow

Data Cleaning and Transformation using Python
Exploratory Data Analysis (EDA)
SQL analysis for business queries
Interactive Power BI dashboards
Business insights and recommendations
Dashboard Pages

1. Executive Dashboard

<img width="1371" height="780" alt="Screenshot 2026-07-24 012236" src="https://github.com/user-attachments/assets/0c36aeb4-d4a4-4e95-9e71-e9e19df49649" />





Provides an overview of key business KPIs including:

Total Sales,
Total Profit,
Total Orders,
Products Sold,
Customers Served,
Profit Percentage,
Monthly Sales Trend,
Monthly Profit Trend.

2. Category Performance Dashboard

<img width="1370" height="793" alt="Screenshot 2026-07-24 012249" src="https://github.com/user-attachments/assets/58126696-d92d-4c75-a8ee-1bb41140c86b" />

Analyzes

Sales by Category,
Profit by Category,
Sales vs Profit comparison,
Cumulative Category Profit,

3. Delivery Partner Dashboard

<img width="1371" height="787" alt="Screenshot 2026-07-24 012259" src="https://github.com/user-attachments/assets/00a64078-077c-4123-84bf-77ab76202e80" />


Monitors

Courier Partner Performance,
Delivery Status,
Distribution of Orders,
Delivery Partner Contribution.

4. Sales vs Target Dashboard

<img width="1368" height="792" alt="Screenshot 2026-07-24 012311" src="https://github.com/user-attachments/assets/b6d2079a-cc7b-4e20-8b72-36e2ceb14ab1" />

Compares

Actual Sales vs Target,
Monthly Sales Performance,
Category-wise Target Achievement,
Year-wise Sales Summary.

Key Business Insights

1. Executive Dashboard

The business generated ₹3.51M in sales from 1,441 orders while serving 1,400 customers.
Overall profit margin is 6.01%, indicating opportunities to improve profitability despite strong sales.
Sales declined from ₹1.25M in January to ₹1.04M in March, highlighting a downward sales trend.
Profit peaked at ₹105K in February, suggesting better pricing or product mix during that month.

Business Recommendation :

Investigate the decline in March sales and replicate the pricing or promotional strategies that contributed to February's higher profitability.

2. Category Performance Dashboard

Electronics generated the highest sales (₹10.54M) but recorded a loss of ₹201K, making it the least profitable category.
Fashion delivered the highest profit (₹523K) despite significantly lower sales, indicating strong margins.
Furniture, Beauty & Personal Care, Home & Kitchen, and Sports & Fitness generated consistent positive profits.
Grocery produced minimal profit, suggesting low contribution to overall business performance.

Business Recommendation :

Review pricing, discount strategies, and operational costs for Electronics to reduce losses.
Increase investment and marketing in Fashion and other high-margin categories to maximize profitability.

3. Delivery Partner Dashboard

Delhivery handled the largest share of deliveries, followed by Ekart.
Delivery volume is concentrated among the top three courier partners.
Monitoring delivery status helps identify delays, cancellations, and return-to-origin (RTO) cases.

Business Recommendation

Strengthen partnerships with the most reliable courier providers while investigating performance issues contributing to delayed or cancelled deliveries.

4. Sales vs Target Dashboard

Overall sales remained slightly below target across the reporting period.
October recorded the highest monthly sales and closely aligned with the sales target.
Some months experienced noticeable gaps between actual sales and planned targets.

Business Recommendation

Analyze seasonal demand patterns and optimize marketing campaigns during low-performing months to improve target achievement.
Business Value

This project demonstrates how business intelligence can help organizations:

Monitor sales performance in real time.
Identify profitable and loss-making product categories.
Optimize pricing and inventory decisions.
Improve logistics and delivery performance.
Track business performance against strategic targets.
Support data-driven decision-making through interactive dashboards.

Project Structure

Indian-Ecommerce-Sales-Analysis/
│
├── Data/
│   ├── Ecommerce_Sales.csv
│   └── Sales_Target.csv
│
├── Python/
│   ├── Data_Cleaning.ipynb
│   ├── EDA.ipynb
│   └── SQL_Analysis.sql
│
├── PowerBI/
│   └── Ecommerce_Sales_Analysis.pbix
│
├── Dashboard_Images/
├── README.md
└── requirements.txt
