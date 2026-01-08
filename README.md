📊 JP Morgan Quantitative Research — Forage

This repository contains my completed work for the JP Morgan Quantitative Research Virtual Experience Program (Forage).
The projects simulate real-world quantitative research tasks across commodity pricing, financial modelling, and credit risk analysis.

Each notebook represents a practical prototype built using Python, data analysis, and quantitative modelling techniques.

🧠 Overview of Tasks
🔹 Task 1 — Natural Gas Price Modelling

File: JP_Tast_1.ipynb

Analyzed historical monthly natural gas prices

Built a trend + seasonality based price estimation model

Created a function to estimate gas prices for any past or future date

Visualized historical trends and future forecasts

Key concepts:
Time-series analysis, seasonality, regression, extrapolation, data visualization

🔹 Task 2 — Pricing a Commodity Storage Contract

File: JP_Task_2.ipynb

Built a prototype pricing engine for a natural gas storage contract

Simulated:

injections & withdrawals

inventory tracking

storage costs

physical constraints (capacity & rates)

Integrated the price model from Task 1

Evaluated multiple storage strategies

Key concepts:
Cashflow modelling, simulation, financial engineering, physical constraints, commodity trading logic

🔹 Task 3 — Credit Risk Analysis (Probability of Default & Expected Loss)

File: JP_Test_3.ipynb

Trained a logistic regression credit risk model

Predicted Probability of Default (PD) from customer features

Evaluated model using accuracy and ROC-AUC

Built a business-facing function 

Key concepts:
Supervised machine learning, credit risk, model evaluation, expected loss, financial decision modelling

🔹 Task 4 — FICO Score Bucketing & Risk Ratings

File: JP_Task_4.ipynb

Designed a quantization framework to convert FICO scores into categorical credit ratings

Implemented:

quantile-based bucketing (baseline)

decision-tree-based optimal bucketing

Calculated PD per FICO bucket

Built reusable functions mapping:

FICO score → Credit rating → Probability of default


Key concepts:
Risk segmentation, quantization, optimal binning, explainable modelling, mortgage risk analysis

🛠 Tools & Technologies

Python

Pandas, NumPy

Matplotlib

Scikit-learn

Google Colab

📌 Key Skills Demonstrated

Quantitative modelling

Financial product pricing

Time-series analysis

Machine learning for risk

Credit risk & expected loss modelling

Data-driven decision systems

Interpretable model design

🎯 About this project

These projects simulate how quantitative researchers work with:

trading desks

risk teams

and model validation groups

to build practical, explainable, and data-driven financial models.
