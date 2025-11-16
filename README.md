# Explainable & Bias-Aware Heart Disease Risk Stratification

This project presents a fully explainable, fair, and calibrated machine learning framework for heart disease prediction. It integrates SMOTE, isotonic calibration, SHAP & LIME explainability, and Fairlearn bias analysis, ensuring performance, transparency, and ethical AI deployment in healthcare.

---

## 🚀 Overview
Cardiovascular diseases remain one of the leading causes of death worldwide. Traditional clinical models often struggle with non-linear data patterns, lack interpretability, and may show bias across demographic groups.

This project addresses these challenges by developing a trustworthy AI framework for heart disease prediction with:

- Explainability (SHAP, LIME)
- Bias mitigation (Fairlearn)
- Probability calibration (Isotonic Regression)
- Class imbalance handling (SMOTE)
- Transparent and clinically reliable predictions

The framework is tested on two benchmark datasets: Cleveland and Statlog Heart Disease datasets.

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
This project successfully demonstrates a trustworthy AI-driven heart disease prediction system by balancing:

✔️ Accuracy

✔️ Fairness

✔️ Interpretability

✔️ Calibration

It addresses the major limitations of current black-box healthcare models and supports real-world clinical decision-making.
