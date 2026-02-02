# [Project 2] AnomalyDetection_BankTransaction
Analysis of Transactional Behavior and Anomaly Detection


# 🏦 Bank Transaction Anomaly & Fraud Risk Analysis

## 📌 Project Overview

Analyzed 2,500+ banking transactions across ATM, Branch, and Online channels to identify anomalous patterns and digital fraud risk using exploratory data analysis

Developed explainable risk indicators and rule-based scoring (high-value transactions, behavioral signals, channel risk) to support fraud monitoring and risk prioritization

Delivered actionable insights enabling risk-based controls, improved auditability, and data-driven decision-making for banking and compliance stakeholders

---

## 🎯 Business Problem
With the growth of digital banking, financial institutions face increased exposure to:
- High-value anomalous transactions
- Online channel fraud risk
- Behavioral abuse (e.g., repeated login attempts, abnormal transaction patterns)



## 📂 Dataset Description
- 2,512 banking transactions
- 16 features, including:
  - Transaction details (amount, type, date)
  - Customer demographics (age, occupation)
  - Behavioral signals (login attempts, transaction duration)
  - Technical context (channel, device ID, IP address)

---

## 🧠 Analytical Approach

### 1. Exploratory Data Analysis (EDA)
- Analyzed transaction amount and account balance distributions
- Compared behavior across channels (ATM, Branch, Online)
- Identified long-tail risk and behavioral outliers
- Observed higher variance and tail risk concentration in **Online transactions**


### 2. Anomaly & Risk Scoring Logic
- Applied **unsupervised, rule-based risk logic** in the absence of labeled fraud data
- Constructed an interpretable **Risk Score** by combining:
  - Transaction magnitude
  - Behavioral anomalies
  - Channel risk exposure
- Classified transactions into **Low / Medium / High Risk** tiers


## 💡 Business Impact
This analysis demonstrates how banks can:
- Prioritize fraud investigation resources more effectively
- Improve auditability and compliance through transparent logic
- Lay the groundwork for scalable, model-driven fraud detection systems

---

## 🧭 Managerial Perspective
From a Data Analytics / Data Science Manager viewpoint, this project highlights:
- Translating EDA into operational risk logic
- Designing explainable and auditable analytics for financial institutions
- Aligning technical analysis with business and compliance needs
- Providing clear insights for stakeholders beyond technical teams

---

## 🛠 Tools & Technologies
- Python (Anaconda)
- Matplotlib
- Jupyter Notebook

---

## 🚀 Future Enhancements
- Integrate labeled fraud data for supervised modeling
- Build real-time dashboards for fraud monitoring teams

Analysis Explaintion
1. First - Statistic exploration and EDA this transaction Data for overview
<img width="680" height="300" alt="image" src="https://github.com/user-attachments/assets/1f86b9f7-7f84-4be7-b6a9-0a579d562432" />

2. Check on graph to find pattern and anormaly data.
   <img width="680" height="300" alt="image" src="https://github.com/user-attachments/assets/e7648cc8-8a7f-4a4e-acc1-7e2979d839ed" />

3. Finally, set the logic formular to detect the suspect transaction
  <img width="680" height="300" alt="image" src="https://github.com/user-attachments/assets/ab68c4d8-f951-46be-839c-7109d876a298" />




