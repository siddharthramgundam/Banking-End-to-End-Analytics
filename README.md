# 🏦 Banking End-to-End Analytics Project

This project is an end-to-end banking data analytics solution that demonstrates
the complete data lifecycle — from database extraction and automated data
preprocessing to exploratory data analysis (EDA) and interactive dashboarding
using Power BI.

The focus of this project is not limited to visualization, but on building a
structured, repeatable, and automation-friendly analytics workflow.

---

## 📌 End-to-End Workflow
MySQL Database  
➡️ SQL Data Extraction  
➡️ Automated Data Cleaning & Transformation  
➡️ Exploratory Data Analysis (EDA)  
➡️ Power BI Dashboard & Insights

---

## 📊 Dataset Information
- Total columns: 24  
- Data source: MySQL database  
- Data type: Banking customer financial data  

---

## 🔧 Data Cleaning & Preparation (Automated)
Data preparation was performed using SQL and Power BI transformation logic.

Key steps include:
- Income categorization into bands:
  - Low
  - Mid
  - High
- Standardization of categorical variables:
  - Gender
  - Nationality
- Mapping encoded values to business-readable formats:
  - Gender:  
    - `1 → Male`  
    - `2 → Female`
  - Branch codes replaced with descriptive branch names
- Conditional columns created to support analytical segmentation

This structure ensures that if new data is added to the database, the same
cleaning logic can be reused without manual rework.

---

## 📉 Exploratory Data Analysis (EDA)
EDA was conducted to understand customer behavior and financial patterns.

### Categorical Analysis
- Gender distribution
- Nationality distribution

### Numerical Analysis
- Credit Card Balance
- Bank Loans
- Bank Deposits
- Checking Account
- Saving Account
- Estimated Income
- Superannuation Savings

---

## 🔍 Key Analytical Insights
- Strong positive correlation observed between:
  - Bank Deposits
  - Checking Account
  - Saving Account
  - Foreign Currency Account
- Customers with high balances in one account type are likely to maintain
  significant balances across other account categories
- Deposit-heavy customers show consistent financial behavior across products

These insights can help banks identify high-value customers and design targeted
financial products.

---

## 📈 Power BI Dashboard Pages
- **Home** – Overall snapshot of banking KPIs  
- **Loan Analysis** – Loan distribution and customer segmentation  
- **Deposit Analysis** – Account balances and correlation trends  
- **Summary** – Consolidated insights from EDA and demographics  

---

## 🚀 Tools & Technologies
- **Database:** MySQL  
- **Data Analysis:** SQL  
- **Visualization:** Power BI  
- **Analytics Logic:** DAX  

---

## 🧠 Key Learnings
- Designing reusable data-cleaning logic for structured datasets
- Performing EDA to extract business-focused insights
- Translating raw financial data into decision-ready dashboards
- Building multi-page Power BI dashboards for stakeholder reporting

---



