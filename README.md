# Sales-analysis-dashboard
## Recommended Structure and Order
### 1.	Project Title / Headline
A concise, descriptive name for the dashboard.
Example: 
🛒 Grocery Store Chain - Sales Analysis Dashboard
A dynamic and interactive Power BI dashboard built to compare sales performance across 9 grocery store branches — focusing on 18 core products spanning 11 major aisles

### 2.	Short Description / Purpose
1–2 sentences explaining what the dashboard does and why it exists.

Example: 
The Grocery Store Chain - Sales Analysis Dashboard is a visually engaging and analytical Power BI report designed to help users explore and compare sales performance across multiple grocery store branches. The dashboard highlights store-wise and product-wise sales trends, top 5 products by sales and quantity, and key KPIs through interactive visuals. This tool is intended for sales analysts, grocery chain managers, and data-driven strategists seeking to uncover performance trends and actionable insight.

### 3.	Tech Stack
List the key technologies used to build the dashboard.

Example:
The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Primary platform for building interactive dashboards and data visualizations.<br>
•	📂 Power Query – Used for data transformation, cleaning, and reshaping to ensure accuracy and consistency.<br>
•	🧠 DAX (Data Analysis Expressions) – Utilized for creating calculated measures such as total sales, total quantity, total customers, and last refreshed date.<br>
•	📝 Data Modeling – Designed a single-table denormalized model optimized for efficient analysis and faster performance.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

### 4.	Data Source
More info on where the data comes from and how it’s structured
Example:
Source:  https://www.kaggle.com/

The dataset contains 1,980 transaction records from a multi-location grocery store chain, capturing detailed sales data across various store locations, product categories, and customer interactions. It spans two years (2023–2025) and provides insights into store performance, product popularity, and purchasing behavior.

The dataset includes information such as store name, product category(aisle), transaction date(sales date), product name, quantity, unit price, and total sales amount, making it ideal for sales performance analysis, trend visualization, and business reporting in Power BI.

### 5.	Features / Highlights
The best dashboard explanation format. 
•	Business problem
•	Goal of the dashboard
•	Walk through of key visuals (briefly!)
•	Business impact & Insights

Example:
•	Business Problem
The grocery retail industry operates across multiple store locations, product categories, and customer segments. However, managers often lack a clear, consolidated view of:

Which stores are performing best over time?
Which products and aisles drive the highest sales and quantities?
How do sales and quantities vary across different time periods (year, quarter, month)?
Which products contribute the most to overall store performance?

•	Goal of the Dashboard

To build an interactive Sales Analytics Dashboard that:
Provides a consolidated view of store, product, and customer performance.
Enables managers to filter and compare results across locations, time periods, and product aisles.
Highlights top-performing products and categories through interactive charts and KPIs.
Reduces manual reporting by delivering a self-service analytics tool for decision-makers.

•	Walkthrough of Key Visuals
- Key KPIs (Top Section)
    Five cards provide instant visibility into overall business performance:
    	Total Sales –$80.88k (Created as a measure for better control and reusability across visuals).
    	Total Quantity Sold - 5797 ( Calculated to track total items sold across transactions).
    	Total Number of Customers – 1779 (Calculated using the DISTINCTCOUNT() function on customer_id).
    	Total Orders – 1955
    	Last Refreshed Date (dynamic card showing the most recent transaction date (sales date) available in the dataset using a DAX measure with the MAX() function).
-	Store & Date Slicers
        Interactive slicers allow filtering the entire dashboard by store location or transaction date (sales date), enabling branch-level and time-based analysis.
-	Product Sales vs. Quantity (Line & Stacked Column Chart)
        A combined column and line visual compares sales revenue with quantity sold across different products, helping identify products that sell in volume vs. value
-	Aisle Sales Distribution (Tree Map Visual)
        Tree map visual displays sales contribution by product categories (e.g., Produce, Dairy, Snacks), making it easy to identify top-performing aisles at a glanceTree map visual displays sales contribution by product categories (e.g., Produce, Dairy, Snacks), making it easy to identify top-performing aisles at a glance.
-	Top Products by Sales & Quantity (Pie & Donut Charts)
        	Pie Chart: Top 5 products ranked by total sales value.
        	Donut Chart: Top 5 products ranked by quantity sold.
        These visuals highlight bestsellers in terms of both revenue and volume.
-	Store-wise Sales Performance (Table Visual)
        A detailed table summarizes store name, total sales, and total quantity, enabling comparison across the 9 store locations.
-	Sales Trends Over Time (Line Chart)
        Line chart displays sales trends by year and quarter, highlighting seasonal patterns and year-over-year growth.
-	Automated Insights (Narrative Visual)
        A narrative visual automatically generates a textual summary of overall sales trends and key insights, supporting faster interpretation for business users.

•	Business Impact & Insights
Sales Performance Tracking: Managers can easily compare sales across store locations and identify which branches are leading or lagging.
Product & Category Analysis: Top products by sales and quantity, along with aisle-level breakdowns, highlight bestsellers and underperforming categories.
Time-Based Trends: Yearly and quarterly trends reveal seasonal patterns and long-term growth opportunities.
Customer & Order Insights: Key KPIs such as total sales, total quantity, total customers, and total orders provide a snapshot of business health.
Decision Support: With slicers, interactive visuals, and smart narrative summaries, stakeholders can make faster, data-driven decisions for inventory planning and store operations.

### 6.	Screenshots / Demos
Show what the dashboard looks like. - ![Alt text]()
Example: ![Dashboard Preview](https://github.com/R-Saran19/Sales-Analysis-Dashboard/blob/main/Dashboard%20Snapshot.png)
