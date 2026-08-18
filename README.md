# 💳 Credit Risk Analysis — Power BI Dashboard

An interactive Power BI dashboard designed to analyze customer behavior, loan portfolio performance, credit risk, default patterns, and financial exposure.

---

## 📌 Project Overview

This project analyzes lending and credit-risk data using Microsoft Power BI.

The dashboard transforms raw loan-level data into an interactive business intelligence solution that helps users understand:

- Customer and loan characteristics
- Loan portfolio distribution
- Default behavior
- Credit-grade risk
- Risk-category exposure
- Loan exposure across income bands
- Financial risk indicators

The dashboard contains three pages:

1. 🏠 Home
2. 👥 Customer & Accounts
3. ⚠️ Risk & Finance

---

## 🎯 Business Objective

The main objective of this project is to provide a clear and interactive view of the loan portfolio and identify areas of higher credit risk.

The dashboard helps answer questions such as:

- Which loan grades have the highest default rates?
- Which risk categories contain the largest loan exposure?
- Which loan intents have higher default rates?
- How does annual income relate to loan amount?
- How is loan exposure distributed across income bands?
- What is the overall default rate?

---

## 🛠️ Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**
- **Microsoft Excel**
- Data Cleaning & Transformation
- Data Visualization
- Business Intelligence

---

## 📊 Dashboard Pages

### 🏠 1. Home

The landing page provides navigation to the two main analytical sections:

- Customer & Accounts
- Risk & Finance

### 👥 2. Customer & Accounts

This page focuses on customer and loan-level analysis.

**Key features:**

- Total Loans
- Total Loan Amount
- Average Interest Rate
- Default Rate
- Loan Distribution by Intent
- Customers by Loan Grade
- Income vs Loan Amount
- Loan Status Distribution
- Customer Snapshot
- Interactive filters

### ⚠️ 3. Risk & Finance

This page focuses specifically on credit risk and financial exposure.

**Key features:**

- Default Rate by Loan Grade
- Loan Exposure by Risk Category
- Default Rate by Loan Intent
- Loan Exposure by Income Band
- High Risk Loan Exposure
- Risk Snapshot
- Risk-based filtering

---

## 📸 Dashboard Preview

### 🏠 Home
Dashboard/Home-page-credit-risk-analysis.png


### 👥 Customer & Accounts


### ⚠️ Risk & Finance


---

## 🔑 Key Insights

Some of the key observations from the dashboard include:

- The overall loan portfolio contains a significant amount of financial exposure.
- Default rates vary considerably across different loan grades.
- Lower-performing loan grades show substantially higher default rates.
- Loan exposure is distributed across multiple risk categories.
- High-risk loans represent a measurable portion of the overall portfolio.
- Default rates vary across different loan intents.
- Income-band segmentation provides another useful perspective on loan exposure.

> **Note:** Dashboard values can change depending on the filters selected by the user.

---

## 💼 Business Recommendations

Based on the analysis:

1. Closely monitor weaker loan grades because they show substantially higher default rates.
2. Investigate loan intents associated with higher default rates.
3. Monitor high-risk loan exposure as both an absolute amount and a percentage of the portfolio.
4. Use income-band analysis to identify potential affordability and concentration risks.
5. Use interactive filtering to investigate specific customer and loan segments.
6. For production implementation, introduce time-based monitoring to track changes in default and risk trends.

---

## 📁 Project Structure

```text
credit-risk-analysis-powerbi/
│
├── Dashboard/
│   ├── Credit-Risk-Analysis.pbix
│   ├── Home-page-credit-risk-analysis.png
│   ├── Customer&Accounts_dashboard.png
│   └── Risk&Finance_dashboard.png
│
├── Report/
│   └── Credit_Risk_Analysis_PowerBI_Report_Updated.pdf
│
└── README.md
