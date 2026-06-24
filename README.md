# DevelopersHub Corporation — AI/ML Engineering Internship Tasks

**Intern:** Muhammad Umer Qureshi  
**Internship:** AI/ML Engineering — DevelopersHub Corporation  
**Due Date:** 26th June, 2026
**Email:** muhammadumerqureshi39@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/muhammad-umer-qureshi-243b12387/
**GitHub:** [muhammadumerqureshi-wq](https://github.com/muhammadumerqureshi-wq)
---

## ✅ Completed Tasks

### Task 1: Exploring and Visualizing a Simple Dataset
- **Dataset:** Iris Dataset (loaded via seaborn)
- **Objective:** Load, inspect, and visualize the dataset to understand data trends and distributions
- **Models Applied:** No model — pure EDA
- **Key Results & Findings:**
  - Dataset has 150 samples, 4 features, 3 species classes
  - Petal length and petal width are the strongest separators between species
  - Setosa is clearly separable; Versicolor and Virginica show some overlap
  - No missing values found in the dataset
- **Skills Used:** pandas, seaborn, matplotlib, descriptive statistics

---

### Task 3: Heart Disease Prediction
- **Dataset:** Heart Disease UCI Dataset (loaded via `ucimlrepo`, id=45)
- **Objective:** Predict whether a patient is at risk of heart disease based on health features
- **Models Applied:** Logistic Regression, Decision Tree Classifier
- **Key Results & Findings:**

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 86.89% | 0.9513 |
| Decision Tree | 78.69% | 0.8047 |

- Logistic Regression outperformed Decision Tree with 86.89% accuracy and ROC-AUC of 0.9513
- Most important features: `cp` (chest pain type), `thalach` (max heart rate), `oldpeak` (ST depression), `ca` (major vessels)
- Age alone is not the strongest predictor — chest pain type and heart rate matter more
- **Skills Used:** binary classification, EDA, ROC-AUC, confusion matrix, feature importance analysis

---

## 🛠️ Tech Stack
- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- ucimlrepo

