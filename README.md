#  Financial Fraud Detection Analysis Dashboard

---

##  Project Overview
The **Financial Fraud Detection Analysis Dashboard** is an end-to-end data analytics project designed to identify fraudulent transactions, uncover hidden patterns, and support decision-making for fraud prevention.

This project leverages **data visualization techniques** to transform raw transaction data into meaningful insights using **Microsoft Excel and Tableau**.

---

##  Problem Statement
Financial institutions face significant losses due to fraudulent transactions. The objective of this project is to:

- Detect anomalies in transaction behavior
- Identify high-risk transaction types and categories
- Analyze fraud trends over time
- Provide actionable insights to reduce fraud risk

---

##  Tools & Technologies
- **Microsoft Excel**
  - Data Cleaning & Transformation
  - KPI Calculation
  - Dashboard Creation
- **Tableau**
  - Interactive Dashboards
  - Advanced Visual Analytics
- **Dataset**
  - Synthetic Financial Transaction Dataset

---

##  Dataset Description

The dataset contains transaction-level data with the following key features:

| Column Name        | Description |
|-------------------|------------|
| step              | Time step (hourly data) |
| type              | Transaction type (CASH_IN, CASH_OUT, TRANSFER, etc.) |
| amount            | Transaction amount |
| nameOrig          | Sender |
| oldbalanceOrg     | Sender balance before transaction |
| newbalanceOrig    | Sender balance after transaction |
| nameDest          | Receiver |
| oldbalanceDest    | Receiver balance before transaction |
| newbalanceDest    | Receiver balance after transaction |
| isFraud           | Fraud indicator (1 = Fraud, 0 = Normal) |
| isFlaggedFraud    | Flagged fraudulent transactions |

---

##  Data Preparation

- Cleaned and validated transaction data
- Created calculated fields:
  - Fraud Rate (%)
  - Fraud Amount
  - Amount Category (Low, Medium, High)
  - Hour extraction from step
- Removed inconsistencies and ensured data accuracy

---

##  Dashboard Preview

### Tableau Dashboard
![Tableau Dashboard](images/tableau_dashboard.png)

###  Excel Dashboard
![Excel Dashboard](images/excel_dashboard.png)

---

##  Dashboard Features

###  KPI Metrics
- Total Transactions
- Total Transaction Amount
- Total Fraud Cases
- Fraud Amount
- Fraud Rate (%)
- Average Fraud Transaction Amount

---

###  Key Visualizations

#### 1. Fraud vs Normal Transactions
- Compares overall fraud distribution

#### 2. Fraud by Transaction Type
- Identifies high-risk transaction categories

#### 3. Fraud by Amount Category
- Highlights fraud concentration in high-value transactions

#### 4. Fraud Trend Over Time
- Tracks fraud patterns across time

#### 5. Hour-wise Fraud Pattern
- Identifies peak fraud hours

#### 6. Fraud by Transaction Type Over Time
- Combines time and transaction behavior analysis

---

##  Key Insights

- **CASH_OUT and TRANSFER transactions** show the highest fraud occurrences
- Fraud is significantly higher in **high-value transactions**
- Fraud patterns fluctuate over time, indicating potential targeted activities
- Specific hours exhibit higher fraud activity, suggesting time-based vulnerabilities

---

## Business Recommendations

- Implement stricter validation for **high-value transactions**
- Enhance monitoring for **TRANSFER and CASH_OUT transactions**
- Introduce **real-time fraud detection systems**
- Use **time-based monitoring** during peak fraud hours
- Improve fraud detection models using behavioral analytics

---


##  Repository Structure


Financial-Fraud-Detection-Dashboard
│
├── Excel Dashboard
├── Tableau Dashboard
├── images
│   ├── excel_dashboard.png
│   └── tableau_dashboard.png
└── README.md

> Note: The dataset is embedded within the Excel and Tableau files.




---

##  Conclusion
This project demonstrates how data analytics and visualization can be effectively used to detect fraudulent activities, uncover hidden patterns, and support proactive decision-making in financial systems.

---

##  Author
**Anjana C**

-  Aspiring Business Analyst
-  Skilled in PowerBI, Excel, Tableau, SQL, and Python
