🏦 Credit Risk Predictor — Automated Loan Risk Assessment & Reporting

A professional credit risk analysis bot that evaluates loan applicants and automatically generates comprehensive PDF reports, including predicted default probability, financial breakdowns, top risk factors, and visualizations for financial analysts or lending institutions.

🚀 What It Does
🔷 Automated Risk Assessment

Accepts loan applicant data interactively (age, income, credit score, employment, debt ratios, loan purpose, and more).

Runs a Random Forest-based calibrated ML model to compute the Probability of Default (PD Score).

Supports both pre-trained models or retraining from CSV datasets if the model is missing.

🔷 Detailed Financial Calculations

Computes loan amortization schedule (monthly principal + interest).

Evaluates monthly payment vs income impact (% of income committed to repayment).

Highlights potential financial stress with color-coded risk thresholds (high risk >35% PD).

🔷 Data-Driven Risk Justification

Extracts top 5 features influencing risk from the ML model.

Provides interpretative notes on each factor (e.g., stability score, income, interest rate).

Helps analysts understand why a loan may be approved or rejected.

🔷 Professional PDF Report

Generates a fully styled PDF with:

Cover and header with date and applicant info

Decision banner with high/low risk visualization

Financial summary (loan, term, monthly payment, PD Score, income impact)

Feature importance table with interpretive notes

Charts:

Probability of repayment vs default

Annual loan amortization (principal + interest stacked)

Payment vs income percentage bar

Ready for internal review or client reporting.

🔷 Production-Ready ML Pipeline

Random Forest Classifier calibrated via Isotonic Regression for robust PD estimation.

Full preprocessing pipeline with:

Median imputation and standard scaling for numeric features

One-hot encoding for categorical features

Feature engineering: Stability Score (CreditScore × MonthsEmployed)

Stratified train-test split ensures balanced evaluation and accuracy tracking.
