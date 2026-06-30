# Predictive Disease Risk Classification

This project builds and compares multiple machine learning models to predict chronic disease risk (diabetes, hypertension, CKD) using public health datasets. The objective is to identify the most reliable modeling approach and the strongest predictive features for early risk identification.

## Models Compared
- Logistic Regression
- Elastic Net
- Random Forest
- Gradient Boosting

Gradient Boosting achieved the strongest performance for diabetes prediction (~0.82 AUC-ROC).

## Evaluation
Model performance was compared using AUC-ROC, F1-score, precision, and recall to assess predictive reliability across approaches.

## Key Findings
Top predictive features identified: BMI, general health rating (GenHlth), income, and physical health (PhysHlth).

## Workflow
- Data cleaning and preprocessing
- Feature engineering and selection
- Model training with cross-validation
- Comparative evaluation across multiple classifiers
- Translation of model results into practical health risk insights
