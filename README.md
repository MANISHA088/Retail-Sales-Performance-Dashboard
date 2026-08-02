# Retail Sales Performance Analytics (SQL + Power BI)
## 📌 Project Overview

Retail businesses collect a large amount of sales data every day, but raw data alone doesn't help managers make better decisions. The goal of this project is to convert sales transactions into meaningful business insights using SQL and Power BI.

This dashboard helps answer questions such as:

Is the business growing over time?
Which products and regions generate the most revenue?
Who are the top-performing sales representatives?
Are new customers more valuable than returning customers?
Which areas need management's attention to improve profitability?
📂 Data Source

This project uses the Sales Dataset available on Kaggle.

Dataset: https://www.kaggle.com/datasets/vinothkannaece/sales-dataset/data

The dataset contains around 1,000 sales transactions recorded during 2023 and includes information about:

Product Category
Sales Representative
Region
Customer Type
Quantity Sold
Sales Amount
Unit Cost
Unit Price
Sale Date
A Note on the Dataset

Since this is a public Kaggle dataset created for practice, I referred to an existing community notebook during the initial exploration to better understand the dataset and its business context.

However, the entire analysis was completed independently. I wrote my own SQL queries, performed the data cleaning, built the Power BI data model, created the DAX measures, designed the dashboard layout, and interpreted the business insights based on my own understanding.

## 🚀 Project Approach

I followed an end-to-end Business Intelligence workflow.

### 1. Data Exploration

Before starting the analysis, I explored the dataset to understand its structure and checked for:

Missing values
Duplicate records
Invalid prices
Invalid dates
Invalid quantities
Data consistency issues

### 2. SQL Analysis
The dataset was imported into SQL Server, where I:

Cleaned and validated the data
Calculated business metrics such as Total Cost, Revenue, Gross Profit, and Profit Margin
Wrote SQL queries to answer key business questions
Created a clean dataset for reporting

### 3. Power BI Dashboard
The cleaned data was connected to Power BI to build an interactive dashboard featuring:

Executive KPI cards
Customer analysis
Product performance
Regional analysis
Sales representative performance
Profitability analysis
Interactive filters
Business recommendations

Rather than creating a dashboard with only charts, I focused on building one that helps answer real business questions and supports decision-making.

### 📊 Key Insights

Some of the key findings from the analysis include:

Clothing and Electronics generated the highest revenue across most regions.
New customers contributed slightly more revenue than returning customers.
Gross profit varied across regions and sales representatives, showing opportunities to improve performance.
Some regions achieved high sales but lower profitability, indicating that increasing revenue alone does not always lead to higher profit.
The performance gap between sales representatives suggests that successful sales strategies can be shared across teams.

### 🛠️ Tools Used
SQL Server
Power BI
Microsoft Excel / CSV

### 💡 Skills Demonstrated
Data Cleaning
Exploratory Data Analysis (EDA)
SQL
Power BI
Data Modeling
Dashboard Design
Business Analysis
Data Storytelling

### 🔮 What I Would Improve
If I had access to more data or additional time, I would extend this project by:

Using multiple years of sales data to analyze long-term trends and seasonality.
Adding customer IDs to study customer lifetime value and retention.
Including discount and marketing cost data to measure true profitability.
Building a proper star schema with separate dimension tables.
Adding sales forecasting and what-if analysis for better business planning.
Connecting Power BI to a live SQL database with scheduled refreshes to simulate a real-world reporting environment.

### 🎯 Project Goal
The goal of this project was to demonstrate an end-to-end data analytics workflow—from data exploration and SQL analysis to building an interactive Power BI dashboard. More importantly, I wanted to go beyond creating visuals and focus on turning data into insights that can support business decisions.
