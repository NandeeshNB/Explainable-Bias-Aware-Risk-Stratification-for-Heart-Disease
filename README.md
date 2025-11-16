# Explainable & Bias-Aware Heart Disease Risk Stratification

A machine learning framework for heart disease prediction that is **accurate, explainable, fair, and calibrated**, built using Random Forest, SHAP, LIME, SMOTE, and Fairlearn.

---

## 🚀 Overview
This project develops a trustworthy AI system for predicting heart disease using the **Cleveland** and **Statlog** datasets. It focuses on:

- Explainability (SHAP, LIME)
- Bias mitigation (Fairlearn)
- Probability calibration (Isotonic Regression)
- Class imbalance handling (SMOTE)
- Transparent and clinically reliable predictions

---

## 🔧 Key Features
- **Preprocessing:** Missing value handling, one-hot encoding, z-score scaling
- **Models:** Logistic Regression, Random Forest (best performer), Decision Tree
- **Imbalance Handling:** SMOTE
- **Calibration:** Isotonic regression
- **Explainability:** SHAP, LIME, surrogate decision tree
- **Fairness:** Evaluation across gender & age groups (DPD, EOD, DIR)

---

## 📊 Results (Best Model: Random Forest)

| Metric | Score |
|--------|--------|
| Accuracy | **0.90** |
| Recall | **0.92** |
| AUC | **0.95** |
| F1 Score | **0.90** |
| ECE (Calibrated) | **0.041** |

### Key Insights
- SMOTE reduced false negatives by **15%**
- Important features: **cp, thalach, oldpeak**
- Fairness metrics within ethical thresholds
- Surrogate decision tree achieved **87% fidelity**

---

## 🧠 Tech Stack
Python · Scikit-learn · SHAP · LIME · Fairlearn · Imbalanced-learn

---

## 🏁 Conclusion
A **fair, interpretable, and calibrated** framework for reliable heart disease risk prediction, suitable for real-world clinical decision support.
