🛒 Adventure Works Sales Insights Using SQL and Power BI

This project presents a structured analysis of the Adventure Works sales dataset using SQL and Power BI.
It highlights critical business metrics such as total sales by product category, order status breakdown, top-selling products, daily sales trends, and much more to uncover actionable business insights.

📁 Dataset Overview:
1. Source: Sales transaction data from the Adventure Works company.
2. Storage: Imported into a MySQL database for query-based analysis.
3. Purpose: Structured Query Analysis and Business Intelligence Reporting through visual dashboards.

🛠️ Tools & Technologies:
| Tool/Library     | Purpose                                         |
|------------------|-------------------------------------------------|
| MySQL            | Data storage, SQL analysis, view creation       |
| Power BI Desktop | Data visualization, Dashboard creation         |
| SQL Scripts      | Data import, exploratory data analysis (EDA), business metrics calculation |

📊 Analysis & Visualizations:

Key business metrics explored
1. 📈 Total Sales by Product Category: Revenue aggregated by product type.
2. 📦 Orders by Status: Analysis of orders by lifecycle stage (Pending, Shipped, Delivered).
3. 🏆 Top-Selling Products: Identification of highest revenue-generating products.
4. 📅 Daily Sales Trends: Daily transaction volume trends over time.
5. 💳 Top Payment Method Adoption: Share of payment methods used in transactions.
6. 💰 Average Price by Category: Mean product pricing across categories.
7. 🏋️‍♂️ Heaviest Products: Top 5 heaviest products analyzed by weight.
8. 📏 Most Common Sizes: Frequently sold product sizes.
9. 🔍 Average Price by Size: Insights on pricing across different size categories.
10. ⚖️ Price-to-Weight Ratio: Comparative visualization of price vs product weight.
11. 📈 Size Impact on Sales: Revenue and quantity sold based on product sizes.

⚙️ Setup Instructions:
1. 📦 Database Setup:
Execute the adventure_works_data_import.sql script to create and populate the Sales table.
Perform exploratory queries using the adventure_works_eda.sql script.
Use the adventure_works_sales_analyse.sql script to build database views for reporting.
Ensure MySQL access with permissions to create databases, tables, and views.
2. 📊 Power BI Setup:
Open the AdventureWorksSales.pbix file in Power BI Desktop.
Connect the Power BI model to your local or server-side MySQL database (SalesDB).
Refresh the data to populate all the dashboards and visuals based on SQL views.

🚀 Future Enhancements:
1. Add advanced KPIs (Customer Lifetime Value, Average Order Value).
2. Build dynamic filters in Power BI for product categories, payment methods, etc.
3. Incorporate time-series forecasting to predict future sales trends.
4. Deploy dashboard to Power BI Service for real-time online access.

📩 Contact:
For feedback, collaboration opportunities, or any queries, feel free to connect!
✨ Thank you for checking out this project! ✨
