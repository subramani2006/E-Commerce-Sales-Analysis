🛒 E-Commerce Sales Analysis

A complete Data Analytics and Exploratory Data Analysis (EDA) project using Python, Pandas, NumPy, and Matplotlib to analyze e-commerce sales performance and generate actionable business insights.

📌 Project Overview

This project analyzes e-commerce transaction data to understand:

- 💰 Revenue and profit performance
- 📦 Product and category performance
- 🌍 Regional sales performance
- 📅 Monthly revenue trends
- 💳 Payment method usage
- 🏷️ Discount and profitability relationships
- 📊 Correlations between numerical variables
- 💡 Business insights and recommendations

The project is implemented in a Jupyter Notebook and includes a PDF report containing the analysis outputs and visualizations.

---

🎯 Objectives

The main objectives of this project are:

1. Calculate important business KPIs.
2. Identify the highest-performing product categories.
3. Find the top-selling products.
4. Analyze sales performance across regions.
5. Study monthly revenue trends.
6. Analyze payment method preferences.
7. Understand the relationship between discounts and profit.
8. Identify correlations between important numerical variables.
9. Provide data-driven business recommendations.

---

🛠️ Technologies Used

Technology| Purpose
Python| Programming and analysis
Pandas| Data manipulation
NumPy| Numerical operations
Matplotlib| Data visualization
Jupyter Notebook| Interactive analysis
CSV| Dataset storage
ReportLab| PDF report generation

---

📂 Project Structure

Ecommerce-Sales-Analysis/
│
├── Ecommerce_Sales_Analysis_Full_Project.ipynb
├── ecommerce_sales_dataset.csv
├── Ecommerce_Sales_Analysis_Project_Report.pdf
└── README.md

---

📊 Dataset

The project uses a reproducible synthetic e-commerce dataset containing 180 orders.

Dataset Features

Column| Description
"Order_ID"| Unique order identifier
"Order_Date"| Date of the order
"Category"| Product category
"Product"| Product name
"Region"| Customer region
"Units"| Number of units purchased
"Unit_Price"| Price per unit
"Discount_Pct"| Discount percentage
"Revenue"| Revenue generated
"Cost"| Product cost
"Payment_Method"| Payment method used
"Profit"| Revenue minus cost
"Profit_Margin_Pct"| Profit margin percentage

---

🔍 Analysis Performed

1. Data Understanding

The notebook checks:

- Dataset shape
- Column names
- Data types
- Missing values
- Duplicate records
- Descriptive statistics

2. Key Performance Indicators

The following KPIs are calculated:

- Total Revenue
- Total Profit
- Total Units Sold
- Average Order Value
- Overall Profit Margin

3. Category Analysis

Revenue, profit, units sold, and profit margin are compared across product categories.

4. Monthly Revenue Analysis

Monthly revenue is calculated and visualized to identify changes in sales over time.

5. Regional Analysis

Revenue is grouped by:

- North
- South
- East
- West

This helps identify regional sales patterns.

6. Product Analysis

The project identifies the Top 10 products by revenue.

7. Payment Method Analysis

Revenue is analyzed according to different payment methods:

- UPI
- Credit Card
- Debit Card
- Cash on Delivery

8. Discount Analysis

The relationship between discount percentage and profitability is analyzed using aggregation and scatter plots.

9. Correlation Analysis

Correlation between numerical variables such as:

- Units
- Unit Price
- Discount
- Revenue
- Cost
- Profit
- Profit Margin

is analyzed.

---

📈 Visualizations

The project includes:

- Revenue by Category
- Monthly Revenue Trend
- Revenue by Region
- Top 10 Products
- Discount vs Profit
- Correlation Matrix

---

💡 Business Insights

The analysis identifies:

- The highest-revenue product category
- The highest-performing region
- The highest-revenue product
- The strongest revenue month
- The highest-revenue payment method
- Overall profitability

These findings can help businesses improve inventory planning, marketing, pricing, promotions, and sales strategies.

---

🚀 How to Run the Project

Step 1: Clone the repository

git clone https://github.com/YOUR_USERNAME/Ecommerce-Sales-Analysis.git

Step 2: Install dependencies

pip install pandas numpy matplotlib jupyter

Step 3: Start Jupyter Notebook

jupyter notebook

Step 4: Open

Ecommerce_Sales_Analysis_Full_Project.ipynb

Step 5: Run all cells

The notebook will load the CSV dataset and perform the complete analysis.

---

📄 Project Report

A PDF report is included:

Ecommerce_Sales_Analysis_Project_Report.pdf

It contains the major analysis outputs, tables, visualizations, findings, and recommendations.

---

🎓 Skills Demonstrated

This project demonstrates practical knowledge of:

- Python
- Data Cleaning
- Data Manipulation
- Exploratory Data Analysis
- Pandas GroupBy
- Data Aggregation
- KPI Analysis
- Data Visualization
- Correlation Analysis
- Business Analytics
- Data-driven Decision Making

---

🔮 Future Improvements

This project can be extended by adding:

- Interactive dashboards using Power BI or Tableau
- Interactive visualizations using Plotly
- Customer segmentation
- Sales forecasting
- Machine learning-based demand prediction
- RFM analysis
- Customer lifetime value analysis
- Real-world e-commerce datasets
- SQL database integration
- Automated reporting

---

👨‍💻 Author

Subramani U

B.Tech Artificial Intelligence & Data Science
Madras Institute of Technology, Anna University

---

⭐ Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.
