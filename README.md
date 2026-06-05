# 📈 Retail Profitability & Credit Risk Analytics

### BDM Capstone Project | IIT Madras BS Degree Program

A complete end-to-end Business Analytics project focused on improving profitability, cash flow, and credit risk management for a neighborhood grocery store using data-driven decision-making.

---

# 🎯 Project Overview

This project was conducted in collaboration with **Faiz General Store**, a family-owned grocery retailer in Prayagraj generating approximately **₹30 lakh annual revenue**.

Although the business maintained stable revenue, analysis revealed significant profitability and liquidity challenges caused by:

* High credit defaults
* Deteriorating cash flow
* Low profit margins
* Poor product portfolio mix

The objective was to diagnose these issues, quantify their financial impact, and design practical business solutions backed by data.

---

# 🏢 Business Context

### Organization

**Faiz General Store**

* Family-owned grocery retailer
* Operating since 1995
* B2C business model
* Serves daily household essentials
* Approximate annual revenue: ₹30 Lakhs

---

# 🚨 Business Problems Identified

## 1. Credit Default Crisis

* ₹40,184 lost due to customer defaults
* 24.5% of gross profit wiped out
* Credit sales created growing liquidity pressure

## 2. Cash Flow Deterioration

* Cash-to-Credit Ratio declined from **3.42** to **1.86**
* Business entered the financial "Warning Zone"

## 3. Profitability Paradox

* Staples generated 57% of revenue
* Margin only 9.25%
* High-margin categories remained underutilized

---

# 📊 Data Collection

All datasets were collected directly from business records and manually digitized.

## Dataset 1: Credit Management

Period:
March 2025 – August 2025

Contents:

* Customer transactions
* Credit amounts
* Payment dates
* Outstanding balances
* Delay information

Records:

* 2,625 credit transactions
* 105 customers

---

## Dataset 2: Category Analysis

Period:
March 2025 – August 2025

Contents:

* Revenue by category
* Cost by category
* Profit margins

Categories:

* Staples
* Snacks
* Personal Care
* Beverages
* Dairy & Bakery
* Cleaning & Household

---

## Dataset 3: Financial Health

Period:
September 2024 – August 2025

Contents:

* Daily Revenue
* Cash Sales
* Credit Sales
* Cost

Records:

* 366 daily observations

---

# 🔍 Methodology

The project followed a complete Business Analytics workflow:

```text
Business Understanding
        ↓
Data Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Analytical Modeling
        ↓
Business Recommendations
        ↓
Impact Projection
```

---

# 🧹 Data Preparation

Performed:

* Missing value treatment
* Data validation
* Standardization
* Feature derivation
* Customer-level aggregation

---

# 📈 Exploratory Data Analysis

Key insights discovered:

### Revenue Patterns

* Weekend revenue approximately 22% higher than weekdays

### Liquidity Trends

* Continuous decline in Cash-to-Credit Ratio

### Profitability Trends

* Stable revenue but weak profitability

### Customer Behavior

* Credit risk highly concentrated among a small customer segment

---

# 🤖 Analytical Models

## 1. Customer Reliability Score Model

Developed a custom Reliability Score (0–100) for advanced credit management.

### Model Structure

Reliability Score =
Default Score + Delay Score

Weight Allocation:

* Default Behavior → 70%
* Payment Delay → 30%

---

## Customer Segmentation

Customers were classified into four risk tiers:

| Tier      | Score Range |
| --------- | ----------- |
| Premium   | 80+         |
| Standard  | 65–79       |
| Watchlist | 50–64       |
| Cash Only | <50         |

This segmentation formed the foundation of the final credit policy.

---

## 2. Dynamic Credit Limit System

A new credit allocation framework was developed:

Credit Limit = Reliability Score × 20

This policy:

* Eliminates credit for high-risk customers
* Rewards reliable customers
* Creates scalable risk management

---

## 3. BCG-Style Strategic Portfolio Analysis

Built a custom BCG Matrix using:

* Revenue Share
* Profit Margin
* Revenue Contribution

Purpose:

* Identify high-margin growth opportunities
* Detect low-margin revenue traps
* Improve category mix

---

# 🔑 Major Findings

## Credit Risk Findings

### High Risk Concentration

* 98% of all financial losses originated from Watchlist and Cash Only customers

### Cash Only Tier

* 28 customers only
* Responsible for 72% of defaults
* Generated approximately ₹28,957 bad debt

### Profitability Impact

Cash Only customers operated at:

-11.8% net profitability

---

## Category Analysis Findings

### Revenue Leader

Staples

* 57% revenue share
* Only 9.25% margin

### Margin Leaders

Personal Care

* 26.6% margin

Snacks

* 20.9% margin

These categories represented significant growth opportunities.

---

## Financial Health Findings

### Cash-to-Credit Ratio

Declined from:

3.42 → 1.86

indicating worsening liquidity conditions.

---

# 💡 Recommendations

## Immediate Actions

### Credit Risk Control

* Remove credit access for Cash Only customers
* Implement Reliability Score framework
* Deploy Dynamic Credit Limit System

---

## Growth Strategy

### Product Portfolio Shift

Increase focus on:

* Personal Care
* Snacks

Reduce over-dependence on low-margin Staples.

---

## Weekend Revenue Strategy

Use weekend traffic surge (+22%) to:

* Promote high-margin products
* Create bundled offers
* Improve profit mix

---

## Customer Retention Strategy

Launch:

* One-month 2% store-wide discount campaign

to ensure smooth transition to the new credit policy.

---

# 📊 Projected Business Impact

| Metric        | Current   | Projected |
| ------------- | --------- | --------- |
| Net Profit    | ₹1,23,804 | ₹1,77,602 |
| Net Margin    | 9.45%     | 13.50%    |
| Profit Growth | —         | +43.4%    |

Projected Additional Profit:

₹53,798+

---

# 🛠️ Tech Stack

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Development Environment

* Google Colab

---

# 📂 Repository Contents

```text
reports/
│
├── Proposal_Report.pdf
├── Midterm_Report.pdf
└── Final_Report.pdf

notebook/
│
└── BDM_Project_Notebook.ipynb

presentations/
│
├── Academic_Presentation.pptx
└── Stakeholder_Presentation.pptx

sample-data/
│
├── Credit_Sample.csv
├── Category_Sample.csv
└── Financial_Sample.csv
```

---

# 📚 Academic Context

This project was completed as part of the **Business Data Management (BDM) Capstone Project** under the **BS in Data Science and Applications Program** offered by **Indian Institute of Technology Madras**.

---

# 👨‍💻 Author

**Mohammad Kashan**

BS in Data Science and Applications

Indian Institute of Technology Madras

LinkedIn: linkedin.com/in/mohammad-kashan-tech

GitHub: github.com/mkashan-tech

Email: [mohammad.kashan.tech@gmail.com](mailto:mohammad.kashan.tech@gmail.com)

---

⭐ If you found this project interesting, feel free to explore the reports, notebook, and presentations included in this repository.
