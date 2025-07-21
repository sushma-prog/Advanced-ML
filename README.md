# 📘 Advanced Machine Learning — End-to-End Learning Pipeline

> **Focus**: Real-world pipelines · Model tuning · SHAP & LIME explainability · API integration · Capstone project deployment

---

## ✅ Week Overview

This week focused on advanced machine learning concepts and practices that go **beyond just training models** — diving into tuning, interpretation, automation, and deployment-level workflow design.

---

## 📅 Day-by-Day Breakdown

### 🔹 **Day 1: Introduction to Gradient Boosting**

- Revisited **bagging vs boosting** principles
- Explored **XGBoost and LightGBM** internals
- Installed and configured libraries
- ✅ Practiced: Trained a basic XGBoost model on the Iris dataset

---

### 🔹 **Day 2: Cross-Validation & GridSearchCV**

- Understood **cross-validation (CV)** strategies: KFold, StratifiedKFold
- Implemented **GridSearchCV** for hyperparameter tuning
- ✅ Practiced: Tuned `max_depth`, `learning_rate`, and `n_estimators` for XGBoost

---

### 🔹 **Day 3: LightGBM & RandomizedSearchCV**

- Compared **LightGBM vs XGBoost**
- Trained a LightGBM model using Breast Cancer dataset
- Used **RandomizedSearchCV** for efficient tuning
- ✅ Practiced: Evaluated and compared both models

---

### 🔹 **Day 4: Model Interpretation with SHAP**

- Learned why interpretability matters in ML
- Used **SHAP** to visualize:
  - Global feature importance (`summary_plot`)
  - Individual prediction reasons (`force_plot`)
  - Feature interactions (`dependence_plot`)
- ✅ Practiced: Visual explanations on Breast Cancer dataset

---

### 🔹 **Day 5: LIME + API Basics**

- Learned how **LIME** provides local explanation for black-box models
- Compared **SHAP vs LIME**
- Used **LimeTabularExplainer** for per-instance interpretation
- Explored **REST APIs**: What they are and how to call them with Python
- ✅ Practiced: Parsed real-time public API like cat facts using `requests` and `json`

---

### 🔹 **Day 6: Building a Mini Data Pipeline**

- Designed an ML **data pipeline**: Ingest → Clean → Model → Export
- Used:
  - `pandas` for preprocessing
  - `xgboost` for modeling
  - `joblib` for saving models
  - `SQLite` & CSV for output storage
- ✅ Practiced: Full pipeline built using Titanic dataset

---

### 🔹 **Day 7: Capstone Project — Customer Churn Prediction**

- End-to-end ML project using **Telco Customer Churn** dataset
- Steps performed:
  1. Load and explore dataset
  2. Clean and encode features
  3. Train-test split + XGBoost with GridSearchCV
  4. Interpret model using SHAP & LIME
  5. Save predictions to **CSV** and **SQLite**
- ✅ Outcome: A complete, interpretable, production-ready ML pipeline

---

## 🎯 Tools & Libraries Used

| Category            | Libraries                          |
|---------------------|------------------------------------|
| Modeling            | `xgboost`, `lightgbm`              |
| Tuning              | `sklearn.model_selection`          |
| Interpretation      | `shap`, `lime`                     |
| Data handling       | `pandas`, `numpy`                  |
| Deployment Ready    | `joblib`, `sqlite3`, `csv`         |
| API Integration     | `requests`, `json`                 |

---

## 📌 Key Skills Mastered

- Gradient Boosting Algorithms
- Model Hyperparameter Tuning
- SHAP & LIME Interpretation
- Data Pipeline Design
- API Calls with Python
- Model & Output Storage (CSV, DB)

---

## 📁 Project Repositories

> ✅ All completed notebooks and projects from this Week are uploaded here:  
🔗 [Advanced-ML]([https://github.com/sushma-prog/customer-churn-prediction](https://github.com/sushma-prog/Advanced-ML)

---

## 👩‍💻 Author

**Sushma Sandanshiv**  
BTech Data Science | Aspiring Data Analyst  
🔗 [LinkedIn](https://www.linkedin.com/in/sushma-sandanshiv-2740422b7/) • 🔗 [GitHub](https://github.com/sushma-prog)

---

