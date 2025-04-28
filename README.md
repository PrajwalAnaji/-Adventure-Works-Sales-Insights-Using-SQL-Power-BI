# 🛒 Adventure Works Sales Insights Using SQL and Power BI
<hr style="height:1px; border:none; background-color:#ccc;">

This project presents a structured analysis of the Adventure Works sales dataset using **SQL** and **Power BI**.  
It highlights critical business metrics such as total sales by product category, order status breakdown, top-selling products, daily sales trends, and much more to uncover actionable business insights.

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 📁 Dataset Overview

- **Source**: Sales transaction data from the Adventure Works company.
- **Storage**: Imported into a **MySQL** database for query-based analysis.
- **Purpose**: Structured Query Analysis and Business Intelligence Reporting through visual dashboards.

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 🛠️ Tools & Technologies

| Tool/Library     | Purpose                                               |
|------------------|--------------------------------------------------------|
| **MySQL**         | Data storage, SQL analysis, view creation             |
| **Power BI Desktop** | Data visualization, Dashboard creation              |
| **SQL Scripts**   | Data import, exploratory data analysis (EDA), business metrics calculation |

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 📊 Analysis & Visualizations

Key business metrics explored:

- 📈 **Total Sales by Product Category**: Revenue aggregated by product type.
- 📦 **Orders by Status**: Analysis of orders by lifecycle stage (Pending, Shipped, Delivered).
- 🏆 **Top-Selling Products**: Identification of highest revenue-generating products.
- 📅 **Daily Sales Trends**: Daily transaction volume trends over time.
- 💳 **Top Payment Method Adoption**: Share of payment methods used in transactions.
- 💰 **Average Price by Category**: Mean product pricing across categories.
- 🏋️‍♂️ **Heaviest Products**: Top 5 heaviest products analyzed by weight.
- 📏 **Most Common Sizes**: Frequently sold product sizes.
- 🔍 **Average Price by Size**: Insights on pricing across different size categories.
- ⚖️ **Price-to-Weight Ratio**: Comparative visualization of price vs product weight.
- 📈 **Size Impact on Sales**: Revenue and quantity sold based on product sizes.

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## ⚙️ Setup Instructions

### 📦 Database Setup:
1. Execute the `adventure_works_data_import.sql` script to create and populate the **Sales** table.
2. Perform exploratory queries using the `adventure_works_eda.sql` script.
3. Use the `adventure_works_sales_analyse.sql` script to build database views for reporting.
4. Ensure MySQL access with permissions to create databases, tables, and views.

### 📊 Power BI Setup:
1. Open the `AdventureWorksSales.pbix` file in **Power BI Desktop**.
2. Connect the Power BI model to your local or server-side **MySQL database** (SalesDB).
3. Refresh the data to populate all the dashboards and visuals based on SQL views.

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 🚀 Future Enhancements

- Add advanced KPIs (Customer Lifetime Value, Average Order Value).
- Build dynamic filters in Power BI for product categories, payment methods, etc.
- Incorporate time-series forecasting to predict future sales trends.
- Deploy the dashboard to **Power BI Service** for real-time online access.

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 📩 Contact

For feedback, collaboration opportunities, or any queries, feel free to connect!

✨ **Thank you for checking out this project!** ✨
