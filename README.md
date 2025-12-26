# Kaggle-diabetes-classification
Kaggle Diabetes Risk Classification & Insights
📌 Project Overview

This project demonstrates an end-to-end data analytics and machine learning workflow, using a large-scale public health dataset from a Kaggle Playground Series competition.

The objective is to predict diabetes risk probability for individuals and translate model outputs into clear, decision-ready insights using an analytical dashboard.

The project emphasises:

Responsible use of model predictions

Clear communication of uncertainty

Practical insight generation rather than raw model scores

🎯 Business / Policy Context

Early identification of high-risk populations can support:

Preventive health planning

Targeted interventions

Resource allocation in healthcare systems

This project is framed as an analytical decision-support exercise, not a clinical diagnostic tool.

📊 Dataset

Source: Kaggle Playground Series (Season 5, Episode 12 – Diabetes Prediction)

Size:

Training data: ~700,000 records

Test data: ~300,000 records

Features include:
Demographics, lifestyle factors, biometric indicators, and medical history.

Target variable: diagnosed_diabetes (binary)

⚠️ Raw datasets are not included in this repository due to size constraints.
The dataset is publicly available on Kaggle.

🤖 Modelling Approach

Baseline model: Logistic Regression

Why Logistic Regression?

Interpretable

Suitable as a strong baseline for risk modelling

Commonly used in health analytics

Model Evaluation

Metric: ROC-AUC

Validation: 5-fold Stratified Cross-Validation

Baseline performance:

Mean ROC-AUC ≈ 0.69

Low variance across folds, indicating stable performance

This baseline establishes a solid foundation for further model experimentation.

📈 Analytics Dashboard (Key Deliverable)

To translate model outputs into insights, predictions were categorised into risk bands and visualised using a dashboard.

Dashboard Highlights

Population distribution by predicted risk band

Total individuals analysed

High-, medium-, and low-risk counts

High-risk proportion KPI

📁 Dashboard file:
dashboard/diabetes-risk-dashboard-model-output.pdf

🔍 Key Insights

Over half of the analysed population falls into the high-risk category

Indicates potential pressure on healthcare systems if risks are not mitigated

Risk stratification enables targeted prevention strategies

⚖️ Ethical Considerations & Disclaimer

Predictions are probabilistic, not clinical diagnoses

Outputs should not be used for individual medical decisions

Intended for analytical, planning, and educational purposes only

Model bias and data limitations must be considered when interpreting results

🛠 Tools & Technologies

Python (pandas, NumPy, scikit-learn)

Kaggle Notebooks

Power BI (dashboarding)

GitHub (version control & documentation)
