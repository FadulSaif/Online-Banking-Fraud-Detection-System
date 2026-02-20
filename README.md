# Online-Banking-Fraud-Detection-System
1. Business Understanding
Goal: Reduce fraudulent online banking transactions while minimizing false alarms.

Business question: Which transactions or sessions are likely fraudulent?

3. Data Understanding
Data tables in SQL Server:

Customers

Accounts

Login events

Transactions

Devices / locations

You explore:

Login frequency

Location changes

Transaction amount anomalies

Time-based behavior

3. Data Preparation

SQL queries to join & aggregate data

Feature engineering (e.g., login count last 24h, transfer amount deviation)

Handling missing values & imbalanced classes

4. Modeling

Baseline: Logistic Regression

Main models: Random Forest or XGBoost

Evaluation: Precision, Recall, F1-score (fraud-focused metrics)

5. Evaluation

Business-focused evaluation (false positives vs missed fraud)

Confusion matrix analysis

Threshold tuning

6. Deployment (Simulated)

Store fraud scores back into SQL Server

Dashboard shows:

Flagged accounts

Fraud risk score

Daily fraud alerts
