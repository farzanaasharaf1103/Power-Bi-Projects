# Costco Wholesale Sales Dashboard 

An end-to-end Sales Analytics Dashboard designed to analyze Costco’s wholesale sales performance across regions, product categories, and customer segments.

The project focuses on business KPIs, profitability, revenue trends, and customer insights, enabling decision-makers to identify growth opportunities and underperforming areas in a highly competitive retail environment.

🚀 Key Business Insights

This dashboard answers critical business questions such as:

💰 What is the total revenue, profit, and quantity sold?

📈 How is Costco performing against revenue targets over time?

🗺️ Which regions and states are driving sales growth, and which are lagging?

🛍️ What is the revenue contribution by product category (Electronics, Furniture, Office Supplies, etc.)?

👥 How do customer segments (Consumer, Corporate, Home Office) impact revenue and profitability?

🎯 Are sales targets being met at regional and product levels?

📊 Dashboard Features

KPI Cards → Quick view of Total Revenue, Profit, and Quantity Sold.

Bookmarks Navigation → Seamless navigation between different views 

Trend Analysis → Line chart showing Revenue vs Target over time.

Regional Insights → US map with state-wise performance.

Category & Segment Analysis → Revenue breakdown by product category and customer segment.

Order vs Target Gauge → Visual representation of progress towards sales goals.

Dynamic Slicers → Filters for Year, Category, and Region.

🛠️ Tech Stack

Data Source → CSV files (Sales, Orders, Products, Regions)

Data Transformation → Power Query for cleaning & preparing data

Business Logic → DAX Measures for KPIs, profitability, and variance analysis

Visualization → Power BI Desktop (Interactive & Storytelling dashboards with bookmarks)

🧩 Hands-On in Power Query

Data preparation was done in Power Query with the following steps:

Removed null values and duplicates across Sales & Orders tables.

Changed data types (date, numeric, categorical) for consistency.

Created calculated columns (e.g., Profit = Sales – Cost).

Built a date dimension table for time-series analysis.


📐 DAX Measures Used

Some of the core DAX measures include:

Total Revenue → SUM(Sales[SalesAmount])

Total Profit → SUM(Sales[Profit])

Quantity Sold → SUM(Sales[Quantity])

Revenue Target % → ( [Total Revenue] / [Target Revenue] ) * 100

YoY Growth → ([Current Year Revenue] - [Previous Year Revenue]) / [Previous Year Revenue]

Profit Margin % → ( [Total Profit] / [Total Revenue] ) * 100


🧑‍💻 Learning Outcomes

Practical experience with Power Query data transformation.

Building DAX measures for KPIs, profitability etc.

Designing regional insights with maps.

Using bookmarks for storytelling navigation in Power BI.

Creating a performance-driven dashboard with targets vs actuals.

# Pizza Store Sales Analytics
An end-to-end Pizza Sales Analytics Dashboard that delivers deep insights into sales performance, revenue trends, customer behavior, and product profitability.

This project simulates a real-world business case where data from an SQL Server database is imported into Power BI, cleaned, transformed, and visualized to empower decision-making in a retail/restaurant setting.

🚀 Key Business Insights

The dashboard enables business users to answer critical questions, such as:

💰 What is the total revenue generated and the average order value?

🥇 Which are the best-performing pizzas by revenue, quantity, and orders?

📉 Which are the worst-performing pizzas that need attention?

📅 What are the daily and monthly sales trends?

🍕 How do pizza categories (Classic, Supreme, Veggie, Chicken) and sizes (Large, Medium, Small, Regular, etc.) impact sales?

⏳ What are the busiest days and peak months for orders?

📊 Dashboard Features

KPI Cards → Showcasing total revenue, average order value, total orders, and total pizzas sold.

Best & Worst Sellers Analysis → Products ranked by revenue, quantity, and order volume.

Daily & Monthly Trends → Identifying busiest days of the week and peak order months.

Category & Size Performance → Sales distribution by pizza type and size.

Interactive Navigation → Using drill-through for seamless navigation between the Home page and Best/Worst Sellers page.

Top & Bottom 5 Analysis → Focused view on best-selling and slow-moving products.

🛠️ Tech Stack

Data Source → Microsoft SQL Server (Import Mode)

Data Visualization → Power BI Desktop

Data Transformation → Power Query (ETL)

Business Logic → DAX Measures for KPIs and trend analysis


🧑‍💻 Learning Outcomes

Practical experience with SQL to Power BI integration.

Hands-on with ETL processes and building reusable DAX measures.

Designing dashboards that highlight actionable insights for business stakeholders.

Applying interactive features like drill-through to improve user experience.

Used Power Query that ensured a clean, consistent, analysis-ready dataset before loading into Power BI.
