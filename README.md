📊 Business Analytics Dashboard using Power BI & DAX

📌 Project Overview

This project focuses on performing descriptive and statistical analysis on business datasets to uncover insights related to e-commerce sales performance and financial risk (loan analysis). Using Power BI, DAX, and Python-prepared data, interactive dashboards were built to support data-driven business decision-making.

🎯 Objectives

Analyze sales trends, customer behavior, and product performance

Understand the impact of discounts on revenue and profitability

Identify high-performing regions, products, and sales channels

Evaluate loan performance and financial risk using customer demographics

Deliver interactive dashboards for business stakeholders

🗂 Datasets Used
E-commerce Sales Data

Customers

Products

Sales

Dates

Financial / Loan Data

Customer_Details

Loan_Details

Date

🧹 Data Cleaning & Preparation

Removed duplicate records (Customer ID, Product ID)

Verified and corrected data types (Date, Discount, Quantity)

Filtered invalid values (zero quantity)

Created derived columns:

Product Amount = Quantity × List Price

Sales Amount = Product Amount − Discount

Categorized data into:

Age groups

Income brackets

Credit score buckets

Discount categories

📐 Key Metrics & DAX Measures
Sales & Customer Metrics

Total Sales

Total Orders

Average Order Value (AOV)

Average Items per Order (AIPO)

Revenue per Customer (ARPC)

Total Profit & Profit Margin

Loan & Risk Metrics

Total Loan Amount

Average Monthly Installment

Defaulted Loans

High-Risk Loans

Loan Status (Active, Closed, Defaulted)

📊 Data Visualization

The Power BI dashboards include:

KPI Cards for sales, orders, customers, and loan metrics

Line Charts for sales and profit trends

Bar & Stacked Charts for regional and category analysis

Donut & Pie Charts for distribution insights

Matrix & Tables for detailed breakdowns

Gauge Visuals for discount and delivery metrics

🔍 Key Insights
Sales & E-commerce

Higher discounts increase sales volume but reduce profit margins

Certain regions outperform others in specific product categories

Standard and Second Class shipping dominate order volume

Same Day delivery shows higher profit margins despite lower volume

Financial & Loan Risk

Customers with low income and poor credit scores show higher default rates

High-risk loans contribute disproportionately to total defaulted amounts

Credit score is a strong indicator of loan performance

🧠 Business Value

Enables targeted marketing and pricing strategies

Supports risk mitigation and loan approval decisions

Helps stakeholders identify growth opportunities and operational risks

Provides interactive exploration through slicers and drill-downs

🛠 Tools & Technologies

Power BI

DAX

Python (Pandas, NumPy)

Excel

📦 Deliverables

Interactive Power BI dashboards

Actionable insights for sales optimization and risk analysis

Dynamic filtering and drill-down capabilities

🔮 Future Enhancements

Add predictive modeling for sales and default risk

Include time-series forecasting

Integrate external economic indicators

Automate data refresh pipelines

🧾 Conclusion

This project demonstrates how data analytics and visualization can transform raw business data into actionable insights, supporting smarter decisions across sales strategy, customer engagement, and financial risk management.
