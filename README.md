# 💳 Credit Card Fraud Risk Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing credit card transaction data to identify fraudulent activities and assess transaction risk using Power BI. The dashboard provides interactive visualizations that help uncover fraud patterns, monitor transaction behavior, and support data-driven fraud prevention strategies.

The dataset was imported from a CSV file and transformed using Power Query before being modeled and visualized in Power BI.
## Dashboard Snapshot

<img width="665" height="370" alt="image" src="https://github.com/user-attachments/assets/109331a3-97ee-4056-8f82-5e01566da513" />
---

## 🎯 Objectives

* Detect and analyze fraudulent transactions.
* Monitor fraud trends over time.
* Identify high-risk transaction categories.
* Compare fraudulent and legitimate transaction behavior.
* Provide insights that can support fraud mitigation efforts.

---

## 📊 Dataset

**Source:** CSV File

The dataset contains credit card transaction records, including:

* Transaction ID
* Transaction Amount
* Transaction Date
* Customer Name
* Merchant Name
* Transaction Type
* Location Data
* Fraud Risk
* Fraud Type
* State
* Card Type
* Bank

---

## 🛠️ Tools Used

* Power BI Desktop
* Power Query
* DAX
* CSV Data Source

---

## 🔄 Data Preparation

The following steps were completed before analysis:

* Imported transaction data from CSV.
* Cleaned and transformed data using Power Query.
* Handled missing and inconsistent values.
* Created calculated columns and measures using DAX.
* Built a data model to support reporting and analysis.

---

## 📈 Dashboard Features

### Executive Summary

* Total Transactions
* Total Fraudulent Transactions
* Fraud Rate (%)
* Total Transaction Value

### Fraud Analysis

* Fraud vs Legitimate Transactions
* Fraud Trends Over Time
* Fraud Distribution by Category
* Fraud Distribution by Location

### Risk Insights

* High-Risk Transactions
* Transaction Amount Analysis
* Customer Risk Segmentation
* Fraud Hotspots

### Interactive Filters

* Fraud Type
* State
* Merchant Name

---

## 🔍 Key Insights

### 1. Card Not Present Fraud is the Most Common Fraud Type
* Card Not Present fraud accounts for the highest transaction volume, with approximately 3 million transactions, making it the leading fraud category. This suggests that online and remote payment channels present the greatest fraud exposure.

### 2. Most Transactions Fall into the Low-Risk Category
* The fraud risk distribution shows that 42.42% of transactions are classified as Low Risk, while only 10.85% are Critical Risk. Although critical cases are fewer, they require immediate investigation due to their higher potential financial impact.

### 3. Gauteng Has the Highest Number of Fraudulent Transactions
* With 149 fraudulent transactions, Gauteng significantly exceeds all other provinces. This indicates that fraud monitoring and prevention efforts should be prioritized in Gauteng.

### 4. Fraud Activity Peaks Towards Year-End
* Fraudulent transactions increase noticeably during the second half of the year, with December recording the highest number of fraud cases (34). This trend may be linked to increased consumer spending and online shopping during the festive season.

### 5. Fraud Rate Remains Materially Significant
* The dashboard reports a fraud rate of 28.6%, indicating that more than one-quarter of analyzed transactions were flagged as fraudulent. This highlights the importance of continuous fraud detection and risk management controls.

## Business Recommendations
* Strengthen fraud controls for online and card-not-present transactions.
* Increase monitoring during peak fraud months, especially November and December.
* Allocate additional fraud investigation resources to Gauteng.
* Prioritize review of Critical and High-Risk transactions.
* Implement real-time alerts for suspicious transaction patterns.

---

## 📂 Project Structure

```text
Credit-Card-Fraud-Risk-Analysis/
│
├── Data/
│   └── credit_card_transactions.csv
│
├── Dashboard/
│   └── Credit_Card_Fraud_Analysis.pbix
│
└── README.md
```

## 📷 Dashboard Preview

<img width="666" height="371" alt="image" src="https://github.com/user-attachments/assets/03bf5cbc-7340-41f9-8e6d-0bcded3fe0f0" />
<img width="665" height="371" alt="image" src="https://github.com/user-attachments/assets/17a96e5b-90e0-40ef-9be9-4273ccbbfc44" />


---

## 🚀 Future Enhancements

* Real-time fraud monitoring
* Machine learning fraud prediction
* Automated risk alerts
* Integration with cloud data sources

---

## 👨‍💻 Author

**Onismus Mamaila**

Data Analyst

---

## 📄 License

This project is intended for educational, learning, and portfolio purposes.
