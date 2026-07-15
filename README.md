# 📊 Customer & Churn Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4c72b0)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

Analyzed customer churn using pandas, numpy, and seaborn to uncover patterns in customer transactions and subscriptions across a 300-customer dataset spanning four related tables.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Approach](#approach)
- [Key Insights](#key-insights)
- [Sample Output](#sample-output)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Overview

This project analyzes customer churn behavior by combining four related datasets — Customers, Churn, Subscriptions, and Transactions — to understand who churns, how they spend, and where they're located. The goal is to move beyond a single churn percentage and understand the patterns behind it: subscription types, transaction habits, and regional distribution.

## Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Handling | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Environment | Google Colab / Jupyter Notebook |

## Dataset

| Detail | Value |
|---|---|
| Total customers | 300 |
| Tables | Customers, Churn, Subscriptions, Transactions |
| Key features | Plan Type, Region, Transaction Amount, Churn Status |

## Approach

1. **Data Integration** — merged Customers and Subscriptions on `CustomerID` to link plan type with customer status
2. **Regional Analysis** — grouped customers by region to understand geographic distribution
3. **Subscription Analysis** — compared Annual vs. Monthly plan counts, and isolated active customers on annual plans
4. **Transaction Analysis** — categorized transactions as "Above $100" or "Below/Equal $100" and visualized the split
5. **Churn Analysis** — calculated total churned vs. not-churned customers and compared the two groups

## Key Insights

- 📉 **33% churn rate** (100 out of 300 customers) — roughly one in three customers has churned, indicating a meaningful retention challenge worth investigating further
- 💳 **57.87% of transactions are above $100**, showing that the majority of customer spending happens at higher transaction values rather than small purchases
- ✅ **82 active customers on annual plans** — annual subscribers make up a substantial share of the active, engaged customer base
- 🌍 **Near-even regional spread**: North America (34.45%), Europe (33.44%), and Asia (32.11%) — no single region dominates the customer base
- 📊 Subscriptions are almost evenly split between Annual (200) and Monthly (199) plans

## Sample Output

**Plan Type Breakdown**

![Plan Type Bar Chart](Plan%20Type%20barchart.png)

**Region Breakup**

![Region Breakup Pie Chart](Region%20Breakup%20Piechart.png)

**Transaction Scatter Plot**

![Scatter Plot](Scatter%20Plot.png)

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/LAXMI15PRIYA/customer-churn-analysis.git
cd customer-churn-analysis

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn

# 3. Launch the notebook
jupyter notebook Customer_Churn_Analysis.ipynb
```

Alternatively, open the notebook directly in Google Colab for zero local setup.

## Project Structure

customer-churn-analysis/
├── Customers.csv                     # Customer demographic data
├── Churn.csv                         # Churn status and reasons
├── Subscriptions.csv                 # Subscription plan data
├── Transactions.csv                  # Transaction history data
├── Customer_Churn_Analysis.ipynb     # Main analysis notebook
├── Plan Type barchart.png            # Annual vs Monthly plan breakdown
├── Region Breakup Piechart.png       # Regional distribution
├── Scatter Plot.png                  # Transaction amount scatter plot
├── README.md
└── LICENSE

## Future Improvements

- [ ] Build a churn prediction model using classification algorithms
- [ ] Analyze churn reasons (Poor Customer Service, High Prices, etc.) to identify the top drivers
- [ ] Segment churned customers by plan type and region to find high-risk segments
- [ ] Add a churn-vs-active comparison chart alongside the existing visuals
- [ ] Add cohort analysis to track retention over time

## Author

**Lakshmi**
M.Tech AI & Data Science | Aspiring Data Analyst / AI Engineer
🔗 [GitHub](https://github.com/LAXMI15PRIYA)

---

⭐ If you found this project useful, consider giving it a star!









