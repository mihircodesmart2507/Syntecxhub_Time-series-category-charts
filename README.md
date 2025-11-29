# Syntecxhub_Time-series-category-charts
Time series and category charts were created to analyze sales trends and compare key categories. Line charts show monthly and quarterly patterns, while bar and pie charts highlight sales by payment mode, sale type, and products. All charts were saved as PNGs, and a summary report was generated for insights.


📁 Project Overview

The notebook performs a complete workflow starting from data import to final visualization export. It includes:

Reading the dataset from Excel/CSV

Cleaning and preparing the data
Creating monthly and quarterly time-series charts
Creating bar and pie charts for categorical comparisons
Saving charts as PNG files
Exporting a short insight summary

This notebook can be used for any sales analytics task involving dates, quantities, and categories. 


📥 Data Preparation

The dataset is loaded using Pandas.

The DATE column is converted to datetime format.

Sales aggregations are created at different levels:

Daily
Monthly
Quarterly

This structured preprocessing ensures accuracy in both trend analysis and visual interpretation.


📈 Time Series Visualization

Time-series charts help identify:

Sales growth patterns
Seasonal fluctuations
High and low-performance periods
Monthly and quarterly trends

Line charts were used because they clearly show how performance changes over time. These visuals provide valuable insights for forecasting and planning. 


📊 Category-Based Charts

Category-level analysis was performed using:

# Bar Charts

Used to compare:

Sales by Payment Mode
Sales by Sale Type
Top Products

This helps identify which categories contribute most to total sales.

# Pie Charts

Used to visualize share contribution for:

Sale Types
Payment Modes

Pie charts make it easy to understand which categories dominate the dataset.

🖼 Exporting Visuals

All generated charts (line, bar, and pie) are exported as high-resolution PNG files, making them ideal for:

Reports
Presentations
Documentation
Dashboards

📄 Summary Report

A short text summary is automatically generated which includes:

Date range covered

Total sales
Average monthly sales
Top performing categories and products

This report provides a concise overview without needing to inspect the entire notebook.

🎯 Purpose of This Project

This notebook demonstrates the practical use of data visualization to convert raw data into actionable insights. By combining time-based and category-based charts, the project gives a complete and meaningful understanding of business performance.

It is ideal for:

Data analysts
Students
Dashboard designers

Anyone learning time series and categorical analysis

📦 Technologies Used

Python
Pandas
Matplotlib
Google Colab
