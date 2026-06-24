# DevelopersHub Corporation — AI/ML Engineering Internship Tasks

**Intern:** Muhammad Umer Qureshi  
**Email:** muhammadumerqureshi39@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/muhammad-umer-qureshi-243b12387/
**GitHub:** [muhammadumerqureshi-wq](https://github.com/muhammadumerqureshi-wq)  
**Internship:** AI/ML Engineering — DevelopersHub Corporation  
**Due Date:** 26th June, 2026

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

### Task 4: General Health Query Chatbot
- **Dataset:** No dataset — Prompt Engineering based
- **Objective:** Build a conversational health chatbot using a Large Language Model
- **Tools:** Groq API (LLaMA 3.3 70B), python-dotenv
- **Key Results & Findings:**
  - Designed professional system prompt controlling persona, tone, and safety rules
  - Built two-layer safety system — keyword filter + LLM-level instructions
  - Implemented conversation memory for context-aware follow-up responses
  - Emergency detection with Pakistan-specific helpline numbers (115, Umang)
  - API key secured via `.env` file and `.gitignore`
- **Skills Used:** prompt engineering, LLM API integration, safety handling, conversational agent design

---

## 🛠️ Tech Stack

### Machine Learning
- scikit-learn (Logistic Regression, Decision Tree, StandardScaler)
- pandas, numpy
- matplotlib, seaborn
- ucimlrepo

### LLM & AI
- Groq API (LLaMA 3.3 70B)
- python-dotenv
- Prompt Engineering

### Environment
- Python 3.14
- Jupyter Notebooks (VS Code)

## 📁 Repository Structure
```
developershub-internship-tasks/
├── task1_iris_eda.ipynb
├── heart_disease_prediction.ipynb
├── task4_health_chatbot.ipynb
├── .gitignore
└── README.md
```
