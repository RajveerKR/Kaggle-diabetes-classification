📊 Dashboard — Predicted Diabetes Risk Insights
Overview

This dashboard presents model-predicted diabetes risk distribution based on a machine learning classification model developed for the Kaggle Playground Series S5E12 – Diabetes Prediction Challenge.

The purpose of this dashboard is to translate model outputs into interpretable population-level insights that can support early intervention planning, risk stratification, and policy discussion.

⚠️ These insights are analytical only and are not intended for clinical diagnosis.


📈 Key Visuals & KPIs
1. Risk Distribution

Visualises the population split across:

High risk

Medium risk

Low risk

Enables quick identification of dominant risk groups.

| KPI                            | Description                                     |
| ------------------------------ | ----------------------------------------------- |
| **Total individuals analysed** | Total records scored by the model               |
| **High-risk individuals**      | Count classified as high diabetes risk          |
| **Medium-risk individuals**    | Count classified as medium risk                 |
| **Low-risk individuals**       | Count classified as low risk                    |
| **High-risk proportion (%)**   | Percentage of individuals in high-risk category |


🧮 Risk Band Logic

Predicted probabilities from the ML model were grouped into risk bands:

High risk: probability ≥ 0.70

Medium risk: 0.40 – 0.69

Low risk: probability < 0.40

These thresholds are used for analytical segmentation only.



🔍 Key Insights

Over half of the population falls into the high-risk category.

This suggests a potential future burden on healthcare systems if risks are not mitigated.

Risk stratification can support:

Targeted prevention programs

Early screening strategies

Resource prioritisation



🛠 Tools Used

Machine Learning: Logistic Regression (scikit-learn)

Evaluation: ROC-AUC with 5-fold cross-validation

Visualisation: Power BI

Data Source: Kaggle Playground Series S5E12 (synthetic dataset)



⚖️ Ethics & Disclaimer

Predictions are generated from synthetic data provided by Kaggle.

Outputs represent statistical risk, not medical diagnoses.

This work is intended for learning, analytics demonstration, and planning insights only.



🔗 Related Links

Kaggle Notebook (Model):
https://www.kaggle.com/code/rajveersandhu/01-baseline-logistic-regression

Kaggle Competition:
https://www.kaggle.com/competitions/playground-series-s5e12
