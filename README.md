Explainable and Bias-Aware Risk Stratification for Heart Disease Using Calibrated Machine Learning Models

This project presents a fully explainable, fair, and calibrated machine learning framework for heart disease prediction. It integrates SMOTE, isotonic calibration, SHAP & LIME explainability, and Fairlearn bias analysis, ensuring performance, transparency, and ethical AI deployment in healthcare.

🔍 Overview

Cardiovascular diseases remain one of the leading causes of death worldwide. Traditional clinical models often struggle with non-linear data patterns, lack interpretability, and may show bias across demographic groups.

This project addresses these challenges by developing a trustworthy AI framework for heart disease prediction with:

✅ High accuracy

✅ Explainable predictions

✅ Fairness across demographic groups

✅ Well-calibrated probability scores

✅ Class-imbalance handling

The framework is tested on two benchmark datasets: Cleveland and Statlog Heart Disease datasets.

🚀 Features
🔹 1. Data Preprocessing

Missing value imputation

One-hot encoding for categorical features

Z-score standardization

Stratified train-test split (80:20)

🔹 2. Imbalance Handling

Synthetic Minority Oversampling Technique (SMOTE)

🔹 3. Models Used

Logistic Regression

Random Forest (Best Performing)

Decision Tree

Hyperparameter tuning using GridSearchCV

🔹 4. Calibration

Isotonic Regression

Reduces probability miscalibration

Improves clinical reliability of predictions

🔹 5. Explainability (XAI)

SHAP: Global + Local explanations

LIME: Instance-level interpretability

Surrogate Decision Tree for model transparency

🔹 6. Bias Mitigation

Using Fairlearn to evaluate:

Demographic Parity Difference

Equal Opportunity Difference

Disparate Impact Ratio

All fairness metrics meet ethical thresholds.

📊 Results
⭐ Best Model: Random Forest
Metric	Score
Accuracy	0.90
Recall	0.92
F1 Score	0.90
AUC	0.95
ECE (After Calibration)	0.041
🔹 Key Findings

SMOTE increased recall by 15% (reducing false negatives).

Important features (via SHAP):

Chest pain type (cp)

Max heart rate (thalach)

ST depression (oldpeak)

Surrogate tree achieved 87% fidelity to the Random Forest model.

Bias metrics across age and gender were within safe limits.
