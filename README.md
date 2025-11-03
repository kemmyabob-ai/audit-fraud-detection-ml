# audit-fraud-detection-ml
Enhancing Audit Efficiency and Fraud Detection Using Machine Learning and Data Analytics”
📘 Overview

This project explores how machine learning can improve audit efficiency and fraud detection using data-driven techniques.
It applies both unsupervised and supervised learning methods on Accounts Payable (AP) and Accounts Receivable (AR) General Ledger (GL) data obtained from an audit client.

The aim is to help auditors move from manual sampling to intelligent, risk-based testing, reducing human review time and improving anomaly detection accuracy.
🧠 Research Objectives

To identify hidden patterns and anomalies in unlabeled General Ledger data using unsupervised learning.

To create pseudo-labels through a cross-model consensus for supervised fraud prediction.

To evaluate and compare the performance of four supervised models:

Decision Tree

XGBoost

LightGBM

CatBoost

To propose an intelligent audit framework that enhances audit efficiency and fraud detection.
🧩 Methodology Summary

This study employs a two-stage hybrid machine learning pipeline:

Stage 1: Unsupervised Discovery
Detects unusual patterns using anomaly detection algorithms applied to unlabeled GL data.

Stage 2: Supervised Prediction
Uses pseudo-labels generated from Stage 1 to train supervised models capable of predicting anomalies with high precision.

Key techniques include feature engineering, data scaling, SMOTE balancing, hyperparameter optimization, and SHAP explainability analysis. 

📊 Data Description

Source: Extracted from the General Ledger (GL) system of an audit client.

Type: Real-world financial data (Accounts Payable and Accounts Receivable).

Privacy: The dataset contains sensitive client information and cannot be shared publicly.

🔍 Key Results

LightGBM achieved the highest ROC-AUC and F1-score on both AP and AR datasets.

SHAP explainability revealed that amount size, transaction frequency, and account-level deviations were top predictors of anomalies.

The approach significantly reduces manual review time while maintaining audit reliability.

🧾 Citation

If you use this project or code in your research, please cite it as:

Diya, K. (2025). Enhancing Audit Efficiency and Fraud Detection Using Machine Learning and Data Analytics. [GitHub Repository].
(https://github.com/kemmyabob-ai/audit-fraud-detection-ml])


🤝 Ethical Statement

This research was conducted in compliance with professional auditing standards, client confidentiality, and institutional data ethics policies. The dataset used contains no personal identifiable information (PII).
