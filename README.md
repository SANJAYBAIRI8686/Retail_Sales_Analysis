## Retail Sales Analysis - SQL Project
![Image Alt](https://github.com/SANJAYBAIRI8686/Retail_Sales_Analysis/blob/main/category_performance.png?raw=true)
Show Image
Show Image

A comprehensive SQL-focused data analysis project demonstrating advanced querying techniques, business intelligence, and data-driven decision making for retail sales optimization.


Project Overview
This project analyzes 9,994 retail orders spanning 4 years (2014-2017) to uncover actionable business insights. Using 80% SQL and 20% Python, the analysis focuses on demonstrating advanced SQL skills including window functions, CTEs, complex joins, and RFM customer segmentation.
##  🎯 Key Objectives

Analyze sales performance trends and patterns
Identify top-performing products, customers, and regions
Segment customers using RFM analysis
Calculate customer lifetime value
Provide data-driven business recommendations


##  🏆 Key Findings
📈 Business Performance


![image alt](https://github.com/SANJAYBAIRI8686/Retail_Sales_Analysis/blob/main/regional_performance.png?raw=true)

Total Revenue: $2,297,201
Total Profit: $286,397
Average Order Value: $229.86
Profit Margin: 12.5%
Total Orders: 9,994
Unique Customers: 793

##  🌟 Top Performers

![image alt](https://github.com/SANJAYBAIRI8686/Retail_Sales_Analysis/blob/main/top_products.png?raw=true)

Best Category: Technology ($836K revenue, 36.4% of total)
Best Region: West ($725K revenue)
Top 10% Customers: Generate 50%+ of total revenue
Peak Season: November-December (holiday shopping)

##  💡 Critical Insights

![image alt](https://github.com/SANJAYBAIRI8686/Retail_Sales_Analysis/blob/main/customer_segments.png?raw=true)

Month-to-month revenue growth of ~8% YoY
80/20 Rule: Top 20% products generate 80% of revenue
Heavy discounting (20%+) reduces profit margins by 35%
Customer retention rate: 67% year-over-year


##  🛠️ Technologies Used
Primary Tools

SQL (SQLite) - 80% of analysis

Complex JOINs (INNER, LEFT, RIGHT)
Window Functions (ROW_NUMBER, RANK, LAG, LEAD, NTILE)
Common Table Expressions (CTEs)
Subqueries and nested queries
Aggregate functions with GROUP BY/HAVING
Date/time functions



##  Supporting Tools

Python 3.8+ - 20% for visualization

pandas - Data manipulation
matplotlib/seaborn - Visualizations
sqlite3 - Database connectivity


DB Browser for SQLite - Query development
Jupyter Notebook - Documentation and reporting


##  📁 Project Structure

```text
retail-sales-sql-analysis/
│
├── README.md                          # Project documentation
├── requirements.txt                   # Python dependencies
│
├── data/
│   ├── Sample - Superstore.csv        # Raw dataset
│   └── retail_sales.db                # SQLite database
│
├── sql/
│   └── retail_analysis.sql            # All SQL queries (12 sections)
│
├── notebooks/
│   ├── 01_Database_Setup.ipynb        # Database creation
│   ├── 02_SQL_Analysis.ipynb          # SQL query execution
│   ├── 03_Visualizations.ipynb        # Python visualizations
│   └── 04_Business_Insights.ipynb     # Final insights report
│
└── images/
    ├── sales_trend.png
    ├── category_performance.png
    ├── top_products.png
    ├── customer_segments.png
    └── regional_performance.png
```





##  🚀 Quick Start
Prerequisites
bashPython 3.8+
SQLite 3.25.0+ (for window functions)
DB Browser for SQLite (optional but recommended)
Installation


Install Python dependencies

bashpip install -r requirements.txt

Download dataset


Download from Kaggle - Superstore Dataset
Place Sample - Superstore.csv in the data/ folder


Create database

bashjupyter notebook notebooks/01_Database_Setup.ipynb
# Run all cells to create retail_sales.db

Run analysis

bashjupyter notebook notebooks/02_SQL_Analysis.ipynb
# Execute SQL queries and view results

📊 SQL Analysis Sections
The project includes 60+ SQL queries organized into 12 sections:
1️⃣ Data Exploration

Table structure analysis
Data quality checks
Date range verification

2️⃣ Basic Business Metrics

Overall performance KPIs
Sales by year/quarter/month
Revenue and profit trends

3️⃣ Product Analysis

Top/bottom performing products
Category and sub-category performance
Profit margin analysis

4️⃣ Customer Analysis

Top customers by revenue
Customer segmentation by value
Purchase frequency distribution

5️⃣ Geographic Analysis

Sales by region, state, city
Regional profit margins
Geographic expansion opportunities

6️⃣ Shipping & Operations

Ship mode performance
Customer segment analysis
Operational efficiency metrics

7️⃣ Discount Analysis

Impact of discounts on profitability
Heavily discounted products
Optimal discount strategies

8️⃣ Advanced Analytics (Window Functions)

Month-over-month growth
Year-over-year comparisons
Running totals
Product ranking within categories

9️⃣ RFM Customer Segmentation

Recency, Frequency, Monetary analysis
Customer scoring (1-5 scale)
Segment classification:

🏆 Champions
💎 Loyal Customers
🌱 Potential Loyalists
⚠️ At Risk
💤 Needs Attention



🔟 Customer Lifetime Value

Total customer value calculation
Average order value by customer
Customer lifespan analysis
Daily value metrics

1️⃣1️⃣ Seasonal Analysis

Monthly seasonality patterns
Day-of-week trends
Holiday season impact

1️⃣2️⃣ Business Intelligence

Pareto analysis (80/20 rule)
Customer retention cohorts
Predictive insights


##  📈 Key Business Recommendations
1. 🎯 Focus on High-Value Customers

Action: Implement VIP loyalty program for top 10% customers (generating 50%+ revenue)
Impact: Increase retention rate from 67% to 75%+
ROI: Estimated $150K additional annual revenue

2. 📦 Optimize Product Portfolio

Action: Discontinue bottom 15 loss-making products
Impact: Reduce inventory costs by $45K annually
Focus: Double down on Technology category (highest margin)

3. 💰 Revise Discount Strategy

Finding: Heavy discounts (20%+) reduce profit margins by 35%
Action: Implement tiered discounting (max 15% for most products)
Impact: Improve overall profit margin from 12.5% to 16%

4. 🌎 Geographic Expansion

Action: Increase marketing spend in West region (strongest performance)
Action: Investigate opportunities in underperforming states
Impact: 20% revenue growth in targeted regions

5. 📅 Seasonal Campaign Planning

Action: Prepare inventory for Q4 spike (Nov-Dec)
Action: Launch retention campaigns in Q1 (lowest sales period)
Impact: Smoothen revenue distribution across quarters


##  📊 Visualizations
Sales Trend Over Time
Show Image
4-year sales and profit trends showing consistent growth
Category Performance
Show Image
Technology leads in both sales and profit margins
Top 10 Products
Show Image
Best-selling products generating the most revenue
Customer Segmentation
Show Image
RFM-based customer segments for targeted marketing
Regional Performance
Show Image
Sales and profit by geographic region

🎓 Skills Demonstrated
SQL Expertise (Primary Focus)
✅ Data Definition Language (DDL)

CREATE, ALTER, DROP statements
Table design and relationships

✅ Data Manipulation Language (DML)

Complex SELECT queries
INSERT, UPDATE, DELETE operations

✅ Advanced SQL Techniques

Window Functions: ROW_NUMBER(), RANK(), DENSE_RANK(), LAG(), LEAD(), NTILE()
Common Table Expressions (CTEs)
Subqueries (correlated and non-correlated)
Multiple JOINs (INNER, LEFT, RIGHT, FULL OUTER)
Aggregate functions with GROUP BY, HAVING
CASE statements for conditional logic

✅ Date/Time Analysis

Date formatting with strftime()
Date calculations with JULIANDAY()
Temporal grouping and trends

✅ Business Analytics

RFM segmentation
Customer lifetime value
Cohort analysis
Pareto analysis
Growth rate calculations

Python Skills (Supporting)
✅ Database connectivity (sqlite3)
✅ Data manipulation (pandas)
✅ Data visualization (matplotlib, seaborn)
✅ Jupyter Notebook documentation

📊 Dataset Information
Source: Kaggle - Superstore Sales Dataset
Description: Retail transaction data from a superstore chain
Size: 9,994 rows × 21 columns
Time Period: 2014-2017 (4 years)
Key Fields:

Order ID, Order Date, Ship Date
Customer Name, Segment
Product Name, Category, Sub-Category
Sales, Quantity, Discount, Profit
Region, State, City
Ship Mode


🔮 Future Enhancements

 Add predictive sales forecasting (ARIMA/Prophet)
 Implement customer churn prediction
 Create interactive Power BI/Tableau dashboard
 Add market basket analysis (association rules)
 Deploy as web app with Streamlit
 Incorporate external data (economic indicators, weather)
 Automated reporting pipeline


##  🙏 Acknowledgments

Dataset provided by Kaggle
Inspired by real-world retail analytics challenges
Built to demonstrate SQL proficiency for data analyst roles


##  📚 Resources
SQL Learning

SQLite Window Functions Documentation
SQL for Data Analysis - Mode Analytics
Advanced SQL - Kaggle Learn

Business Analytics

RFM Analysis Guide
Customer Lifetime Value Calculation



<div align="center">
⭐ If you found this project helpful, please give it a star! ⭐
Built with 💻 SQL, 📊 Data, and ☕ Coffee
⬆ Back to Top
</div>

