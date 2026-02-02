# Bank Loan Analytics – End-to-End Data Analyst Project

##  Project Overview
This project analyses bank loan data to understand loan performance, borrower risk, and overall loan portfolio health.  
The objective is to support data-driven lending decisions by identifying good vs bad loans, monitoring repayments, and analysing key risk indicators.

The project simulates a real-world banking analytics use case, following a complete workflow from raw data cleaning to SQL-based analysis and interactive Power BI dashboards.

---

##  Business Problem
Banks process thousands of loan applications through multiple channels such as online portals, internal systems, and third-party credit bureaus.  
Managing loan portfolios without proper analytics makes it difficult to assess credit risk, identify defaults, and monitor portfolio performance.

This project addresses key banking challenges such as:
- Assessing borrower creditworthiness
- Monitoring loan repayment performance
- Identifying high-risk loans and potential defaults
- Supporting data-driven lending and risk management decisions

---

## Dataset Description
The dataset contains historical bank loan information, including:
- Loan application details
- Borrower financial and employment information
- Loan amount, interest rate, and term
- Debt-to-Income (DTI) ratio
- Loan status (Fully Paid, Current, Charged Off)
- Repayment and transaction details

 *This dataset is used for educational and analytical purposes.*

---

## 🔄 Loan Lifecycle Covered
The analysis aligns with the complete loan lifecycle:
- Loan application and borrower evaluation  
- Credit risk and affordability assessment  
- Loan approval and disbursement  
- Repayment tracking  
- Ongoing monitoring of loan status and defaults  

---

##  Data Pipeline & Workflow
This project follows a complete end-to-end analytics workflow:

### 1️ Data Cleaning & Preparation
- Cleaned raw bank loan data using **Excel**
- Handled missing values, corrected data types, and standardized formats
- Performed data validation to ensure accuracy and consistency before analysis

### 2️ Database Storage (SQL Server)
- Uploaded the cleaned dataset into **SQL Server**
- Structured tables to store loan, borrower, and repayment information
- Used SQL queries for data extraction, aggregation, and KPI calculations

### 3️ Power BI Integration
- Connected **Power BI directly to SQL Server**
- Built the data model on top of SQL tables
- Created DAX measures and interactive visuals for analysis

 Power BI dashboards are built on SQL Server data, reflecting a production-style analytics setup.

---

##  Tools & Technologies Used
- **Excel** – Data cleaning and preprocessing  
- **SQL Server** – Data storage, querying, aggregations, KPI calculations  
- **Power BI** – Interactive dashboards and data visualization  

---

## Key KPIs & Metrics Analysed
- Total Loan Applications  
- Total Funded Amount  
- Total Amount Received  
- Month-to-Date (MTD) and Month-over-Month (MoM) metrics  
- Average Interest Rate  
- Average Debt-to-Income (DTI) Ratio  
- Loan Status Distribution (Good vs Bad Loans)  
- Monthly Loan Application Trends  

---

##  Key Insights
- Identified seasonal trends and growth patterns in loan applications  
- Analysed loan term distribution (36 vs 60 months) to understand repayment risk  
- Evaluated borrower risk using interest rate and DTI metrics  
- Highlighted portfolio exposure across loan purposes and geographic regions  
- Provided a clear view of overall loan portfolio health and performance  

---

##  Dashboard Overview
The Power BI dashboard provides a comprehensive summary of the bank’s loan portfolio and borrower risk profile.

### Key Dashboard Components:
- **Executive KPIs:** Total Loan Applications, Total Funded Amount, Total Amount Received, Average Interest Rate, Average DTI  
- **Trend Analysis:** Monthly loan application trends to identify demand patterns  
- **Loan Term Analysis:** Comparison between 36-month and 60-month loans  
- **Borrower Profile Analysis:** Loan distribution by employment length and home ownership  
- **Geographic Analysis:** State-wise loan application distribution  
- **Purpose Analysis:** Funded amount by loan purpose such as debt consolidation, credit cards, and home improvement  

Dashboard screenshot is uplaoded in the file.
---

## Project Structure
```text
 Bank-Loan-Analytics
│──  Data
│   └── bank_loan_data.csv
│──  SQL
│   └── loan_analysis_queries.sql
│──  Dashboard
│   └── Bank_Loan_Report.pbix
│   └── bank_loan_dashboard_summary.png
│── README.md
