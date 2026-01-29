# Credit Risk Modeling & Loan Default Prediction (End-to-End)

## Overview
This project builds an end-to-end credit risk modeling pipeline to estimate the probability of loan default using real-world lending data. The objective is not only to achieve strong predictive performance, but also to demonstrate interpretability, business reasoning, and decision-making aligned with banking practices.

The project follows a structured workflow used in financial institutions, covering data understanding, feature engineering, statistical modeling, evaluation, and threshold selection based on business cost considerations.

---

## Why This Project Matters
Credit risk modeling is a core function in banks and financial institutions. Decisions made using such models directly affect:
- capital preservation
- loan approval policies
- profitability and risk exposure

Unlike stock price prediction or purely accuracy-driven ML tasks, this project emphasizes:
- probability estimation
- explainable models
- asymmetric cost of errors
- business-aligned evaluation metrics

---

## Dataset
- **Source:** LendingClub Loan Dataset (Kaggle)
- **Type:** Real historical loan applications
- **Target Variable:** Loan default (Charged Off vs Fully Paid)
- **Scale:** ~1.3 million resolved loans

Only information available **at loan approval time** is used to prevent data leakage.

## Data Availability

The raw LendingClub dataset and processed data files are not included in this repository due to GitHub file size constraints.  
The dataset can be downloaded from Kaggle and the processed data can be reproduced by running the feature engineering notebook.


---

## Project Structure
