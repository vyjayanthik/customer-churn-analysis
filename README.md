# Customer Churn Analysis

## Overview

This project analyses customer churn behaviour using the IBM Telco Customer Churn dataset.
The goal was to identify which customer segments are most at risk of leaving and translate 
those patterns into actionable business recommendations.

Dataset: 7,043 customer records, 21 features
Domain: Telecom / Customer Retention
Status: Analysis complete — Power BI dashboard in progress

## Tools Used

Python, Pandas, Matplotlib, Jupyter Notebook

## What I Analysed

- Overall churn rate across the full customer base
- Churn breakdown by contract type (month-to-month vs 1-year vs 2-year)
- Churn behaviour across customer tenure stages
- Relationship between monthly charges and churn likelihood
- Customer segmentation by pricing tier (low, medium, high)

## Key Findings

Contract type turned out to be the strongest predictor of churn.
Month-to-month customers churn at around 42%, compared to roughly 11% for customers 
on 2-year contracts. That's nearly a 4x difference — a significant retention opportunity 
for any business that can nudge customers toward longer commitments.

Tenure matters just as much. Customers in their first year are around 3 times more 
likely to churn than long-term customers. The data suggests that if a customer makes 
it past the 12-month mark, they're far more likely to stay.

Higher monthly charges also correlate with increased churn. Customers paying above 
the mid-range threshold showed noticeably higher exit rates, pointing to a price 
sensitivity issue that retention strategies could target directly.

## Business Recommendations

Incentivise contract upgrades — the churn gap between month-to-month and long-term 
contracts is large enough to justify targeted discount offers or loyalty perks for 
customers who agree to a 1 or 2-year plan.

Build a proper onboarding programme for new customers — the first 12 months are 
the highest-risk window. Early engagement, check-ins, or welcome incentives could 
meaningfully reduce that first-year churn rate.

Identify and prioritise high-charge customers at risk — customers paying more 
are both high-revenue and higher-churn risk. A personalised retention outreach 
for this segment is a relatively low-cost, high-return intervention.

## Files in This Repo

Customer Churn Analysis.ipynb — full analysis with code and visualisations
Customer Churn Analysis.html — rendered version, viewable without Jupyter
Telco Customer Churn.csv — the source dataset

## How to Run

git clone https://github.com/vyjayanthik/customer-churn-analysis
cd customer-churn-analysis
jupyter notebook "Customer Churn Analysis.ipynb"

## Coming Soon

An interactive Power BI dashboard is currently in development.
It will include churn rate KPI cards, contract type and tenure breakdowns, 
monthly charge distribution, and filters by service type and customer profile.
The published dashboard link will be added here once complete.

## About

Built by Vyjayanthi Kadapanatham — MSc Data Science (Distinction), University of Hertfordshire.
Open to graduate and junior Data Analyst roles in the UK.
