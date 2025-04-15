
# 🛡️ Financial Fraud Detection & Risk Analysis

This project analyzes online banking transaction data to identify potentially fraudulent behavior using rule-based logic, data cleaning, and visual analytics.

## 📌 Objective

To detect suspicious transactions using defined fraud rules and score-based risk assessment. The project simulates a real-world Business Analyst role, using data cleaning, risk modeling, KPI dashboards, and Agile project tracking.

---

## 🧰 Tools & Technologies

- **Excel** – Data profiling, manual rule flagging, conditional logic
- **Python (Pandas)** – Data cleaning, type conversion, feature engineering
- **SQL** – Fraud rule logic and querying high-risk accounts
- **Tableau** – Fraud score heatmaps, time series, KPI dashboards
- **Jira** – Agile simulation, user story documentation

---

## 🔍 Fraud Detection Logic

Implemented 6+ rule-based fraud detection methods:

| Rule Type                  | Description                                          |
|---------------------------|------------------------------------------------------|
| High Transaction Amount    | > 90th percentile threshold                         |
| Rapid Transactions         | Multiple transactions within short time (e.g., 5 min) |
| Login Anomalies            | Excessive login attempts                             |
| New Device or IP Address   | Unrecognized DeviceID or IP for account             |
| Geolocation Mismatch       | Transactions from unexpected locations              |
| Teen High-Value Spending   | Outlier transactions for age group                  |

Each rule assigned a binary flag (1 = suspicious), contributing to a **Fraud Score** out of 6.

---

## 📊 Visualizations (Tableau)

Key dashboards created:

- 📈 **Fraud Score Heatmap** – High-risk accounts by score
- 🧭 **Location-Based Risk** – Top risky geographies
- 🕐 **Time Series Trend** – Suspicious transaction frequency over time
- 📌 **RiskLabel Pie Chart** – High risk vs. normal breakdown

![Dashboard Preview](tableau/dashboard_screenshot.png)

---

## 📁 Repository Structure
- `data/`: Sample or anonymized dataset
- `notebooks/`: Python code for cleaning and analysis
- `excel_reports/`: Fraud flags and manual rule checks
- `tableau/`: Dashboard screenshots and visuals
- `jira/`: Sample task board and workflow
fraud-detection-risk-analysis/ ├── README.md ├── data/ │ └── sample_data.csv ├── notebooks/ │ └── fraud_cleaning_analysis.ipynb ├── excel_reports/ │ └── fraud_score_flags.xlsx ├── sql/ │ └── fraud_rules_queries.sql ├── tableau/ │ └── dashboard_screenshot.png ├── jira/ │ └── project_tasks_screenshot.png
