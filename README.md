# Healthcare Fraud Detection Analytics Project

## Overview
This project analyzes healthcare insurance claims data to identify fraud patterns using SQL and Python.

The analysis includes:
- Fraud trend analysis
- Provider specialty risk analysis
- Claim amount segmentation
- Window functions
- Ranking analysis
- Moving averages
- Risk scoring

---

## Tools & Technologies
- SQL (DuckDB)
- Python
- Pandas
- Jupyter Notebook
- GitHub

---

## Dataset Features
- Claim Amount
- Provider Specialty
- Fraudulent Claim Flag
- Length of Stay
- Previous Claim History
- Claim Submission Delay

---

## Key SQL Concepts Used
- GROUP BY
- CASE WHEN
- CTEs
- Window Functions
- RANK / DENSE_RANK / ROW_NUMBER
- LAG / LEAD
- Moving Average
- Aggregations

---

## Key Insights
- Short hospital stays had the highest fraud percentage.
- Cardiology and Orthopedics showed unusually high fraud rates in short stays.
- Mid-range claim amounts had higher fraud percentages than very high or very low claims.
- Fraud trends fluctuated monthly but remained consistently high over time.

---

## Project Structure
