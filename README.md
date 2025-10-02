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
  
<img width="961" height="444" alt="Screenshot (173)" src="https://github.com/user-attachments/assets/dcd8124d-76c9-4fa8-b8b1-b7e738437ae6" />
 
<img width="662" height="787" alt="Screenshot (175)" src="https://github.com/user-attachments/assets/bfa57bd3-bd30-44c4-9df7-736cc2e3c65f" />

### ML 

- **Scatter Plot:** 
<img width="833" height="552" alt="Screenshot (176)" src="https://github.com/user-attachments/assets/a8a639c6-1761-4152-94f1-0157863f139b" />

- **Boxplots:** 

<img width="1031" height="532" alt="Screenshot (177)" src="https://github.com/user-attachments/assets/68b0abfb-3f98-4474-9ae2-03a3762ecc5c" />


- **Heatmap:**
<img width="910" height="533" alt="Screenshot (174)" src="https://github.com/user-attachments/assets/2b1dfcd2-cfda-4c6f-93cb-b84d70a7e314" />

## Conclusion from SQL Analysis

* Total transactions analyzed: 2,500+ records with debit and credit operations.
* Debit transactions had higher frequency, while credit transactions contributed larger amounts.
* Online channel showed the highest average transaction value, signaling higher fraud risk.
* Top 5 locations accounted for a majority of high-value transactions → potential hotspots (Fort Worth).
* Average account balance by occupation- Doctor hold higher balances.
* Login attempt analysis revealed that higher attempts often aligned with higher transaction values, a fraud red flag.
* Location-based net balance change showed some cities as deposit-heavy (net positive) while others were spending-heavy (net negative).

## ER Diagram 

![ER Diagram](https://github.com/Aastha-collab/Financial-Fraud-Detection--PROJECT-/blob/main/ER%20diagram-%20Fraud%20Analysis.png)

## Conclusion from Power BI Visualization 

<img width="1268" height="717" alt="Screenshot (170)" src="https://github.com/user-attachments/assets/4e656d8f-ffd5-4b81-ac97-4f827d2d96e6" />

<img width="1269" height="713" alt="Screenshot (171)" src="https://github.com/user-attachments/assets/05987e4f-a7ed-4af1-aedb-7d625c8ed6fc" />

<img width="1291" height="706" alt="Screenshot (172)" src="https://github.com/user-attachments/assets/84bed4df-1896-493c-99b7-fca052ff1f17" />

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
