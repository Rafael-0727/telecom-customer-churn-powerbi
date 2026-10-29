<img width="1346" height="756" alt="Age Groups" src="https://github.com/user-attachments/assets/d81bddf0-7d80-40e0-b5fc-d51e80a569f5" /><img width="1462" height="862" alt="Overview" src="https://github.com/user-attachments/assets/55655932-858a-4730-8dff-6b518d398d52" /># Telecom Customer Churn Analysis (Databel)

## Executive Summary
This project analyzes customer attrition for Databel, a telecommunications provider, to identify primary churn drivers and propose targeted retention strategies. The interactive Power BI dashboard examines customer demographics, contract types, account charges, and call usage across 6,600+ accounts.

## Key Insights
* **The International Plan Anomaly:** Customers paying for an international plan who had zero international call activity experienced an alarming churn rate (>71%), compared to standard baseline churn (~20%).
* **Contract Durations:** Month-to-month contracts demonstrated the highest rate of customer departures compared to 1- and 2-year commitments.
* **Customer Service Friction:** Accounts with 3 or more customer service calls showed a steep inflection point in churn probability, as the number of customers per group increased the number of churn rate decreased, pointing to a Negative correlation between those factors.

## Tech Stack & Methods
* **Tool:** Power BI Desktop
* **DAX Formulas:** Custom measures using `DIVIDE`, `CALCULATE`, and `COUNTROWS` for dynamic churn metrics.
* **Data Modeling:** Categorical tiering and consumption binning using `SWITCH(TRUE(), ...)` logic.

## Dashboard Preview

### 1. Executive Churn & Contract Overview
<img width="1462" height="862" alt="Overview" src="https://github.com/user-attachments/assets/ed0cb45a-2af9-4033-b6b1-15afc6acd328" />

### 2. International Plan & Service Analysis
<img width="1920" height="1080" alt="International Plan   Service Analysis" src="https://github.com/user-attachments/assets/9c04c8c8-f56a-4447-8a02-e0402203a98e" />

### 3. Pricing & Group Tier Distribution
<img width="1346" height="756" alt="Age Groups" src="https://github.com/user-attachments/assets/505f2417-7408-4c0c-a6dd-41347209beb5" />
