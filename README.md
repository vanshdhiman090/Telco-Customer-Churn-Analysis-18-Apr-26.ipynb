# Telco Customer Churn Analysis
### A Business Analytics Project using the Google Data Analytics Framework

---

## Project Overview
This project analyzes customer churn for a telecom company using a dataset 
of 7,043 customers. The goal is to identify which customers are most likely 
to leave, understand the key drivers behind churn, and deliver actionable 
recommendations to improve retention and protect revenue.

---

## Business Problem
> "Why are customers churning, which segments are most at risk, and what 
actions can the business take to reduce churn and protect revenue?"

**Stakeholder:** Head of Growth at a telecom/fintech startup
**Goal:** Deliver 3 data-driven retention recommendations

---

## Dataset
| Detail | Info |
|---|---|
| Source | IBM via Kaggle |
| Rows | 7,043 customers |
| Columns | 21 features |
| Target Variable | Churn (Yes/No) |
| License | Open — educational use only |

🔗 [Dataset Link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## Framework
This project follows the **Google Data Analytics 6-phase framework:**

| Phase | Description |
|---|---|
| Ask | Defined business problem and stakeholder |
| Prepare | Assessed data credibility (ROCCC), ethics, and bias |
| Process | Cleaned data — missing values, type fixes, duplicates |
| Analyze | Explored churn drivers using Python and SQL |
| Share | Visualized findings for non-technical stakeholders |
| Act | Delivered 3 concrete business recommendations |

---

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (SQLite)
- Jupyter Notebook
- GitHub

---

## Key Findings
1. **26.53% overall churn** — 1 in 4 customers are leaving
2. **Contract type is the #1 driver** — month-to-month churns at 42.70% vs 2.83% for two-year contracts
3. **New customers are highest risk** — 61.99% churn in month 1
4. **Electronic check users churn at 45.29%** — 3x higher than automatic payment users
5. **Fiber optic churn at 41.89%** — highest among all internet service types
6. **No online security = higher churn** — 41.77% vs 14.61% with security
7. **Annual revenue at risk: $1,669,570**

---

## Business Recommendations

### 1. ⚡ Convert Month-to-Month Customers to Annual Contracts
Month-to-month customers churn at 15x the rate of two-year customers.
Offer discounts or incentives to switch — converting 20% would recover
$300K+ annually.

### 2. 📅 Build a 90-Day Onboarding Program
61.99% churn in month 1 signals customers leave before seeing value.
A structured onboarding program with proactive support touchpoints
would dramatically reduce early churn.

### 3. 📅 Push Auto-Pay Adoption + Bundle Online Security
Electronic check users churn at 45.29% vs 15-17% for auto-pay users.
Incentivize switching to automatic payments and bundle online security
into base plans to improve retention.

---

## Project Structure
