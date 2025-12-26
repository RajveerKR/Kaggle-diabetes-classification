# Model Summary – Diabetes Risk Classification

## Objective
To predict the probability of diabetes diagnosis using demographic, lifestyle, and clinical indicators, based on the Kaggle Playground Series S5E12 dataset.

## Dataset
- Training records: 700,000
- Test records: 300,000
- Target variable: `diagnosed_diabetes` (binary)
- Features include age, BMI, blood pressure, cholesterol levels, lifestyle factors, and medical history.

## Model Approach
- Baseline model: Logistic Regression
- Preprocessing:
  - Categorical variables encoded
  - Numerical features scaled
- Evaluation method: 5-fold Stratified Cross-Validation

## Model Performance
- Mean ROC-AUC (CV): **~0.69**
- Standard deviation: **~0.001**
- The model provides stable and consistent predictive performance across folds.

## Risk Stratification
Predicted probabilities were grouped into three risk bands:
- **High risk**
- **Medium risk**
- **Low risk**

This enabled population-level risk analysis and downstream dashboarding.

## Outputs
- Kaggle submission file (`submission.csv`)
- Power BI dashboard visualising:
  - Risk distribution
  - High-risk proportion
  - Population counts by risk band

## Notes & Limitations
- Predictions are probabilistic and not clinical diagnoses.
- The model is intended for analytical and planning purposes only.
- Further performance gains may be achieved using tree-based or ensemble models.

