# Customer & Churn Analysis 📊

Analyzed customer behavior, subscription trends, and churn patterns using Python, Pandas, Matplotlib, and Seaborn.

## 🔍 What I Worked On
- Data loading and preprocessing from multiple datasets (Customers, Churn, Subscriptions, Transactions)
- Data filtering and segmentation (region-wise, active vs inactive customers)
- Exploratory Data Analysis (EDA) using visualizations
- Customer churn analysis and comparison
- Subscription trend analysis (Annual vs Monthly)
- Transaction analysis based on spending patterns

## 📌 Key Insights
- Total customers analyzed: **300**
- Region breakdown: North America (103, 34.45%), Europe (100, 33.44%), Asia (96, 32.11%)
- Active customers in Europe: **47**
- Subscription split: Annual (200) vs Monthly (~199) — almost evenly distributed
- 57.87% of transactions were above $100, 42.13% were $100 or below
- Churned customers: **100** vs Retained customers: **200** (33% churn rate)
- Active customers on Annual plans: **82** — a key high-value segment

## 🛠️ Tools & Skills Used
Python | Pandas | NumPy | Matplotlib | Seaborn | Data Cleaning | EDA | Data Visualization

## 📈 Steps Involved

**1. Data Loading**
Imported libraries (Pandas, NumPy, Matplotlib, Seaborn) and loaded 4 datasets: Customers, Churn, Subscriptions, Transactions

**2. Data Exploration**
Viewed datasets using `.head()`, selected specific columns (FirstName, LastName), filtered customers by region

**3. Customer Analysis**
- Total customers: 300
- Region-wise distribution visualized with a pie chart
- Active vs inactive customer breakdown by region (e.g., 47 active customers in Europe)

**4. Subscription Analysis**
- Filtered Annual plan users (200 total)
- Compared Annual vs Monthly using bar charts — found an almost equal distribution (~200 each)

**5. Transaction Analysis**
- Filtered transactions above $100 (125 transactions, 57.87%)
- Created a new `Amount_Category` column (Above 100 / Below or Equal 100)
- Built a pie chart, bar chart, and scatter plot to visualize spending patterns

**6. Churn Analysis**
- Total churned customers: 100
- Not churned: 200
- Visualized churn vs retention using a bar chart (33% churn rate)

**7. Data Merging**
- Merged customers + subscriptions data
- Found 82 active customers with an Annual plan — a valuable customer segment to target for retention

## 📊 Charts Created
- **Region Breakup** — Pie chart showing customer distribution across North America, Europe, and Asia
- **Subscriptions: Annual vs Monthly** — Bar chart comparing plan types
- **Transaction Amount Pie Chart** — Above $100 vs Below/Equal $100
- **Transaction Bar Chart** — Count of transactions by amount category
- **Scatter Plot** — Transaction amounts across all records, colored by category
- **Churn vs Not-Churned** — Bar chart comparing churned vs retained customers

## 📂 Files
- `Customer_Churn_Analysis.ipynb` — main analysis notebook
- `Customers.csv`, `Churn.csv`, `Subscriptions.csv`, `Transactions.csv` — datasets used

## 💡 Takeaway
This project strengthened my ability to extract meaningful insights from raw data and present them visually — skills I'm looking to apply to real-world business problems.
