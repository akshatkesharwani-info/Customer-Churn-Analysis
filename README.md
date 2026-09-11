# Customer Churn Analysis

A diagnostic analysis of why telecom customers churn -- built to answer "why are we losing
customers" before jumping to a predictive model.

## Problem
A telecom provider is losing subscribers and needs a plain-language explanation of the drivers,
not just a churn percentage, so retention strategy can be built on evidence instead of guesses.

## What It Does
- Cleans and prepares the Telco Customer Churn dataset (7,043 real customers)
- Breaks churn rate down by contract type, tenure band, payment method, and internet service
- Correlates churn against tenure, monthly charges, and total charges
- Builds simple, explainable customer segments from spend

## Real Results (real dataset, 7,043 rows)
- **Overall churn rate: 26.6%**
- Tenure is negatively correlated with churn (**-0.35**) -- the longer someone stays, the less
  likely they are to leave
- Monthly charges are positively correlated with churn (**+0.19**) -- higher bills, higher risk
- Total charges are negatively correlated (**-0.20**), consistent with tenure driving loyalty

## Tech Stack
Python, Pandas, Seaborn, Matplotlib

## How to Run
Open in Google Colab, run all cells. Dataset auto-downloads via `kagglehub`; falls back to a
synthetic sample automatically if the download ever fails.
