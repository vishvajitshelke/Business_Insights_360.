# Business Insights 360 - Power BI Dashboard

## Short Project Summary
This project is a comprehensive Power BI dashboard for AtliQ Hardware, designed to analyze performance across Finance, Sales, Marketing, and Supply Chain departments. It provides a 360-degree view of business health to support data-driven decision-making.

---

# Problem Statement
The management team lacked a centralized system to track departmental performance, making it difficult to identify loss-making products, evaluate customer growth, and monitor inventory risks like "Out of Stock" or "Excess Inventory".

---

# Objective
The goal is to provide stakeholders with actionable insights through a logical flow of views—starting from high-level executive summaries down to granular department-level details.

---

# Tools & Technologies
- Power BI – Data visualization and reporting
- SQL (MySQL) – Data storage and extraction
- Excel – Supplementary data and mapping
- DAX – Complex measures and calculated columns
- Power Query – ETL (Extract, Transform, Load) processes

---

# Dataset Information
- Source: MySQL Database and Excel files containing sales, financial, and supply chain data
- Data Scope: Historical data spanning from 2019 to 2022 (Estimated)

---

# Process / Workflow

## 1. Data Collection
Imported data from MySQL and Excel into Power BI.

## 2. Data Cleaning
Used Power Query to handle missing values, format dates, and create helper columns.

## 3. Data Modeling
Established a Star/Snowflake schema to connect dimension and fact tables.

## 4. Visualization
Designed a multi-page dashboard with a consistent UI/UX theme.

## 5. Insights Generation
Analyzed trends to identify key growth drivers and operational bottlenecks.

---

# Key KPIs / Metrics
- Net Sales – Total revenue generated
- Gross Margin % – Product profitability after COGS
- Net Profit % – Final profitability after all expenses
- Forecast Accuracy – Precision of supply chain predictions
- Net Error – Difference between forecast and actual sales

---

# Dashboard / Project Screenshots

| View Name | Image Reference |
|------------|----------------|
| Home Page | Home.jpg |
| Executive View | Executive View.jpg |
| Finance View | Finance View.jpg |
| Sales View | Sales View.jpg |
| Marketing View | Marketing View.jpg |
| Supply Chain View | Supply Chain View.jpg |

---

# Key Insights
- Net Sales reached $3.74bn, which is 353.5% higher than the benchmark
- North America (NA) is the leading region with $1,022.1M in sales
- Maintained a Forecast Accuracy of 81.17%
- Net Profit shows a negative trend (-13.98%), indicating a need for expense optimization

---

# Business Impact
- Improved Planning – High forecast accuracy helps reduce inventory costs and stockout situations
- Transparency – Management can monitor all departments from a centralized dashboard
- Faster Decisions – Interactive filters enable real-time analysis of customers and regions

---

# Folder Structure

```plaintext
/data       # Raw datasets (Excel/SQL scripts)
/dashboard  # Power BI .pbix file
/sql        # SQL queries for data extraction
/images     # Dashboard screenshots
README.md   # Project documentation
