# 📊 Sales Insight Project

A data analysis project to evaluate and visualize sales performance using SQL and Power BI.

![Dashboard Preview](Sales%20DashBoard-1.png)

<br>

## 🧠 About the Project

This project analyzes sales performance across different products, markets, and timeframes. It uses Power BI for dynamic reporting, helping identify sales trends and business opportunities.

<br>

## 🎯 Project Objectives

- Develop an insightful and interactive dashboard to evaluate key sales metrics.
- Analyze:
  - Year-on-Year revenue growth.
  - How different regions are performing and which are the top ones.
  - The top-performing products and top customers of the company.

<br>

## 📁 Dataset Information

- **Source**: Provided SQL dump
- **File**: `db_dump.sql`
- [📄 View SQL Dump](db_dump.sql)

<br>

## 🛠️ Tools & Technologies Used

- **Database**: MySQL
- **Visualization**: Power BI
- **IDE**: MySQL Workbench

<br>

## 🧹 Data Preprocessing

- Imported the database dump into MySQL and explored the table structures.
- Exported the data to Power BI for visualization.
- Cleaned and standardized data formats such as date formats, null handling, and currency formatting.
- Created calculated measures like **Average Order Value**, **Average Order Quantity**, **Total Revenue**, and **Quantity Sold**.

<br>

## 📊 Exploratory Data Analysis (EDA)

- Created calculated measures for metrics like **Average Order Value**, **Average Order Quantity**, **Total Revenue**, and **Quantity Sold**.
- Used slicers and filters for better interactivity (e.g., by country or category).
- Analyzed overall sales performance, regional performance, top-performing products, and top customers.

<br>

## 📈 Visualizations

- Designed a simple Power BI dashboard to highlight business relevant metrics.
- Included KPI cards to display key values like **Average Order Value**, **Average Order Quantity**, **Total Revenue**, and **Quantity Sold**.
- Created bar charts showing year-on-year revenue, top 5 products, top 5 customers, and the distribution of sales between own brand and distribution.
- Added a map to highlight regions based on their sales performance.


- [🗂️ View Power BI File](Sales%20DashBoard.pbix)

  ![Dashboard Preview](Sales%20DashBoard-1.png)

<br>

## 🔍 Key Insights & Conclusions

- The company has generated a total revenue of 984.4M to date, selling a total of 2.4M products.
- The company's year-on-year revenue has shown a significant decline since 2018 and continues to fall.
- Delhi, Mumbai, and Ahmedabad are some of the top-performing regions, with Delhi being the highest.
- Electricalsara Stores is the top customer of the company, contributing around 50% of the total revenue. This highlights a major disparity in customer sales and an over-dependence on a single customer.

<br>

## 📝 Recommendations

- The sales dependency on a single customer, Electricalsara Stores, is a major concern. This disparity must be addressed by focusing on acquiring more high-value customers to balance sales and reduce dependency.
- The company should also focus on targeting low-performing regions by allocating more marketing budgets to counter the revenue decline and drive positive growth.
- Top-performing products should be marketed more aggressively to further boost sales.
