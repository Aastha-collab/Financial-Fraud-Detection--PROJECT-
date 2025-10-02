##  Project Title

**Fraud Detection Project – Financial Transaction Anomaly Detection**

##  Team Members

* **Aastha Yadav** – Excel pivot tables & visualizations, SQL & Python visualizations support
* **Aditya Bajantri** – Python (data cleaning, preprocessing, ML models), Excel processing
* **Aman Singh** – SQL database queries & management
* **Rajshri** – Power BI dashboard creation

---

## Goal & Objective

* **Goal**: To analyze financial transaction data and detect fraudulent activities using analytics and machine learning.
* **Objective**: To build an end-to-end fraud detection system combining **data cleaning, SQL, EDA, ML anomaly detection, visualization, and dashboards** for business insights.

---

##  Tools & Technologies

* **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
* **SQL** (queries for fraud patterns, KPIs, aggregations)
* **Excel** (data cleaning, pivot tables, initial analysis, charts)
* **Power BI** (interactive dashboards for business insights)
* **Machine Learning** (Isolation Forest, PCA, DBSCAN for anomaly detection)

---

## Conclusion from Python

### EDA 

- Conducted **scatter plots** of `TransactionAmount` vs `CustomerAge` to visualize unusual transactions.  
- Used **boxplots** for categorical features (e.g., `CreditCard`, `Online`, `Student`) to identify feature-level anomalies.  
- Observed that anomalies are rare (~5–6% of transactions), consistent with real-world fraud rates.

![ER Diagram](images/er_diagram.png)

![ER Diagram](images/er_diagram.png)

![ER Diagram](images/er_diagram.png)

![ER Diagram](images/er_diagram.png)

### ML 

- **Scatter Plot:** `TransactionAmount` vs `Anomaly Score` highlighted fraudulent transactions in red.  
- **Boxplots:** Showed anomalies concentrated in certain categorical groups, e.g., online transactions and specific user types.  
- **Heatmap:** Illustrated deviations in numeric features across flagged transactions. 


## Conclusion from SQL Analysis

*Total transactions analyzed: 2,500+ records with debit and credit operations.
*Debit transactions had higher frequency, while credit transactions contributed larger amounts.
*Online channel showed the highest average transaction value, signaling higher fraud risk.
*Top 5 locations accounted for a majority of high-value transactions → potential hotspots (Fort Worth).
*Average account balance by occupation- Doctor hold higher balances.
*Login attempt analysis revealed that higher attempts often aligned with higher transaction values, a fraud red flag.
*Location-based net balance change showed some cities as deposit-heavy (net positive) while others were spending-heavy (net negative).

## ER Diagram 

![ER Diagram](images/er_diagram.png)

## Conclusion from Power BI Visualization 

![ER Diagram](images/er_diagram.png)

![ER Diagram](images/er_diagram.png)

![ER Diagram](images/er_diagram.png)

## 

---

##  Project Workflow

1. **Data Collection & Cleaning** – Removed duplicates, handled nulls, standardized features.
2. **Exploratory Data Analysis (EDA)** – Transaction trends, spending patterns, anomalies visualized in Excel & Python.
3. **SQL Analysis** – Queries for suspicious patterns (e.g., multiple logins, high-value transactions, frequent attempts).
4. **Machine Learning** – Isolation Forest & DBSCAN to detect anomalies; PCA for dimensionality reduction.
5. **Evaluation** – Accuracy, precision, recall, F1-score; flagged anomalies reviewed.
6. **Visualization** – Power BI dashboards, Python plots, and Excel pivot tables for insights.

---

##  Key Insights

* Identified **suspicious high-value transactions** with low balances.
* Detected unusual **time-of-day transaction spikes**.
* Found patterns where **multiple login attempts** were linked to anomalies.
* Highlighted occupations & customer segments more prone to fraudulent activity.

---

##  Deliverables

* **Raw Data (CSV)** – original transactions
* **Clean Data (Excel)** – processed with pivot tables & charts
* **Python Files** – ML model implementation (EDA + Isolation Forest/DBSCAN)
* **SQL Scripts** – fraud-related queries & ER diagram
* **Power BI Dashboard** – interactive anomaly detection visualization

---

##  Learning Outcomes

* Hands-on experience with **fraud analytics in real-world datasets**
* Practical use of **unsupervised ML models for anomaly detection**
* Integration of **Excel, SQL, Python, and BI tools**
* Enhanced teamwork & cross-functional collaboration
* Strong preparation for **interviews, case studies, and data analytics roles**

---
