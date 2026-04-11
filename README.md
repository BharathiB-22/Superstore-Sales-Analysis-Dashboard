📊 Superstore Sales Analysis Dashboard
🔍 Project Overview

This project analyzes a retail Superstore dataset using Power BI to generate actionable business insights. The dashboard focuses on sales performance, profitability, customer behavior, and shipping efficiency to support data-driven decision making.

📁 Dataset Information
Source: Kaggle – Superstore Sales Dataset
Format: CSV
Records: ~50,000+ rows
Columns: ~20–22
Key Fields:
Order Details: Order ID, Order Date, Ship Date, Order Priority
Customer Info: Customer Name, Segment
Location: Country, State, Region, Market
Product Info: Category, Sub-Category, Product Name
Metrics: Sales, Profit, Quantity, Discount, Shipping Cost
🧹 Data Cleaning (Excel)
Removed duplicate records
Checked and handled missing values
Converted data types (Date, Numeric, Text)
Created new column:
Profit Margin = Profit / Sales
Extracted Year from Order Date
🔗 Data Modeling
Single-table dataset used
No relationships required
Optimized for direct visualization in Power BI
📊 Dashboard Explanation (Chart-wise)
📌 Page 1: Executive Overview
KPI Cards
Total Sales, Profit, Orders, Customers
👉 Gives a quick snapshot of overall business performance
Line Chart (Sales & Profit Trend)

👉 Shows monthly growth pattern
👉 Helps identify seasonal trends

Donut Chart (Sales by Segment)

👉 Consumer segment contributes the highest sales
👉 Home Office is the lowest contributor

Bar Chart (Sales by Market)

👉 APAC and US generate highest revenue
👉 Canada & Africa are low-performing markets

Map (Sales by Country)

👉 Visual geographic distribution of sales

Scatter Plot (Discount vs Profit)

👉 High discount → Low or negative profit
👉 Shows inefficient pricing strategy

📌 Page 2: Sales Analysis
Bar Chart (Sales by Sub-Category)

👉 Top products: Phones, Copiers
👉 Low sales: Binders, Machines

Column Chart (Sales by Year & Category)

👉 Sales increasing year by year
👉 Technology category growing fastest

Line Chart (Monthly Sales Trend)

👉 Peak sales in later months (Nov–Dec)
👉 Seasonal demand pattern observed

Segment Analysis

👉 Consumer segment dominates sales
👉 Corporate segment steady growth

📌 Page 3: Profit & Cost Analysis
Waterfall Chart (Profit by Sub-Category)

👉 Shows contribution of each product to total profit
👉 Some products reduce overall profit

Scatter Plot (Sales vs Profit)

👉 High sales doesn’t always mean high profit
👉 Identifies low-margin products

Bar Chart (Profit by Region & Category)

👉 Some regions perform better in specific categories

Combo Chart (Sales vs Discount)

👉 High discounts reduce profitability

Funnel Chart (Order Priority)

👉 Most orders are Medium priority
👉 Critical orders are very few

📌 Page 4: Customer & Shipping Analysis
Bar Chart (Top Customers)

👉 Few customers contribute large revenue (Pareto effect)

Donut Chart (Sales by Segment)

👉 Consumer segment dominates again

Bar Chart (Shipping Cost by Ship Mode)

👉 Standard class used most
👉 Same-day shipping least used

Line Chart (Delivery Days Trend)

👉 Delivery time varies monthly
👉 Possible logistics inefficiency

Stacked Bar (Orders by Region & Ship Mode)

👉 Standard shipping dominates across regions

🎯 Key Insights
High discounts reduce profitability
Consumer segment is the largest revenue contributor
APAC & US are top-performing markets
Some products generate high sales but low profit
Shipping cost impacts overall margins
Few customers contribute majority of revenue
🛠 Tools Used
Power BI
Microsoft Excel
📂 How to Use

Download the .pbix file and open it in Power BI Desktop to explore interactive dashboards.

🎓 Key Learnings
Data cleaning & preprocessing
Dashboard design & storytelling
Business insight generation
Data visualization best practices
