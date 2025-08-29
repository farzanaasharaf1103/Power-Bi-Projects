**Costco Wholesale Sales Dashboard**

An end-to-end Power BI dashboard developed to analyze Costco’s wholesale sales performance across regions, product categories, and customer segments. The dashboard delivers strategic insights into business KPIs, profitability, and customer behavior in a competitive retail environment.

**Key Findings**
- Total revenue, profit, and quantity sold were calculated and visualized for quick reference.
- Revenue performance was tracked against targets over time using dynamic trend analysis.
- Regional performance was mapped, highlighting states driving growth and those underperforming.
- Product category contributions (Electronics, Furniture, Office Supplies, etc.) were broken down to assess profitability.
- Customer segments (Consumer, Corporate, Home Office) were analyzed for their impact on revenue and profit margins.
- Sales target achievement was monitored at both regional and product levels.

**Dashboard Features**
- KPI Cards for Total Revenue, Profit, and Quantity Sold
- Bookmarks for seamless multi-page navigation
- Line Chart for Revenue vs Target trend analysis
- US Map for state-wise regional insights
- Bar Charts for category and segment-level breakdowns
- Gauge Visual for order vs target tracking
- Dynamic Slicers for Year, Category, and Region filtering

**Technical Implementation**
- Data Source: CSV files (Sales, Orders, Products, Regions)
- Data Preparation: Power Query
- Removed nulls and duplicates
- Standardized data types
- Created calculated columns (e.g., Profit = Sales – Cost)
- Built a date dimension table for time-based analysis
- Business Logic: DAX Measures
- Total Revenue → SUM(Sales[SalesAmount])
- Total Profit → SUM(Sales[Profit])
- Quantity Sold → SUM(Sales[Quantity])
- Revenue Target % → ([Total Revenue] / [Target Revenue]) * 100
- YoY Growth → ([Current Year Revenue] - [Previous Year Revenue]) / [Previous Year Revenue]
- Profit Margin % → ([Total Profit] / [Total Revenue]) * 100
- Visualization Tool: Power BI Desktop

**Learning Outcomes**
- Gained hands-on experience with Power Query for data transformation
- Built DAX measures for KPIs, profitability, and growth analysis
- Designed regional insights using map visuals
- Applied bookmarks for storytelling navigation
- Created performance-driven dashboards with target tracking


**Pizza Store Sales Analytics**
A Power BI dashboard designed to analyze pizza sales performance, customer behavior, and product profitability using data imported from SQL Server. The project simulates a real-world restaurant scenario and supports operational and strategic decisions.

**Key Findings**
- Total revenue, average order value, total orders, and total pizzas sold were calculated and visualized.
- Best-performing pizzas were identified by revenue, quantity sold, and order volume.
- Underperforming pizzas were flagged for further review and potential optimization.
- Daily and monthly sales trends revealed peak ordering periods and busiest days.
- Pizza categories (Classic, Supreme, Veggie, Chicken) and sizes (Large, Medium, Small, Regular) were analyzed for their impact on sales.
- Top and bottom 5 products were highlighted to support inventory and marketing decisions.

**Dashboard Features**
- KPI Cards for Revenue, Average Order Value, Total Orders, and Pizzas Sold
- Best & Worst Sellers Analysis using ranked visuals
- Daily & Monthly Trend Charts
- Category & Size Performance Breakdown
- Drill-through Navigation between summary and detail views
- Focused Top & Bottom 5 Product Analysis

**Technical Implementation**
- Data Source: Microsoft SQL Server (Import Mode)
- Data Preparation: Power Query
- Cleaned and transformed data for consistency
- Ensured analysis-ready dataset before loading into Power BI
- Business Logic: DAX Measures for KPIs and trend analysis
- Visualization Tool: Power BI Desktop

**Learning Outcomes**
- Integrated SQL Server data into Power BI
- Applied ETL processes using Power Query
- Built reusable DAX measures for business metrics
- Designed dashboards with actionable insights
- Enhanced user experience with drill-through navigation


