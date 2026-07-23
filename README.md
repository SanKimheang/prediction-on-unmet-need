# 📊 Predicting Unmet Need for Family Planning using Machine Learning

A machine learning project that predicts the **Unmet Need for Family Planning (UNFP)** using socio-demographic data from the **Cambodia Demographic and Health Survey (CDHS)**. The project compares multiple classification algorithms to identify women who are likely to have an unmet need for family planning and analyzes the most influential factors through feature importance analysis.

---

## 📌 Project Overview

Unmet need for family planning remains a significant public health challenge in many developing countries. Early identification of women at risk can support policymakers and healthcare providers in designing targeted interventions and improving access to reproductive health services.

This project develops several machine learning models to classify whether a woman has an unmet need for family planning and compares their predictive performance.

---

## 🎯 Objectives

- Predict unmet need for family planning using socio-demographic characteristics.
- Compare the performance of multiple machine learning models.
- Establish Logistic Regression as the baseline model.
- Identify the most influential predictors using feature importance analysis.
- Provide data-driven insights to support healthcare policy and planning.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- XGBoost
- Matplotlib
- Seaborn
- Feature Importance
- Jupyter Notebook

---

## 📂 Dataset

The project uses data from the **Cambodia Demographic and Health Survey (CDHS)**.

### Dataset Characteristics

- **Total observations:** 6,226
- **Features:** 71
- **Target Variable:** Unmet Need for Family Planning (Binary)

Target Classes:

- **0** → No Unmet Need
- **1** → Unmet Need

The dataset contains demographic, socioeconomic, reproductive health, and family planning-related variables.

---

## 🔄 Project Workflow

```
CDHS Dataset
      │
      ▼
Data Cleaning & Preprocessing
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Feature Engineering
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
 ┌──────────────┐
 │ Logistic Reg │
 ├──────────────┤
 │ Random Forest│
 ├──────────────┤
 │ LightGBM     │
 ├──────────────┤
 │ XGBoost      │
 └──────────────┘
      │
      ▼
Model Evaluation
      │
      ▼
Feature Importance Analysis
      │
      ▼
Policy Insights
```

---

## 🤖 Machine Learning Models

### Logistic Regression (Baseline)

A simple and interpretable linear classification model used as the baseline for performance comparison.

### Random Forest

An ensemble learning method that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

### LightGBM

A gradient boosting framework optimized for speed and efficiency, capable of handling large datasets and complex feature interactions.

### XGBoost

An advanced gradient boosting algorithm known for its high predictive performance and regularization capabilities.

---

## 📊 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

Performance comparison was conducted to identify the best-performing model for predicting unmet need.

---

## 🔍 Feature Importance Analysis

Feature importance analysis was performed to understand which variables contribute most to the prediction.

Methods used include:

- Feature Importance (Tree-based Models)
- SHAP (SHapley Additive Explanations)

The analysis provides interpretable insights into the key socio-demographic factors associated with unmet need for family planning.

---

## 📈 Results

The project compares four machine learning models to determine the most effective approach for predicting unmet need for family planning.

> Replace the placeholders below with your actual results and visualizations.

### Model Performance Comparison

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|--------|---------:|----------:|--------:|---------:|---------:|
| Logistic Regression | 8.833 | 6.302 | 6.961 | 6.615 | 9.384 |
| Random Forest | 8.951 | 6.244 | 9.020 | 7.380 | 9.651 |
| LightGBM | 9.283 | 7.756 | 7.908 | 7.832 | 9.718 |
| XGBoost | 9.288 | 7.818 | 7.843 | 7.830 | 9.705 |

---

## ▶️ Usage

Run the notebooks sequentially:

1. Data Preprocessing
2. Exploratory Data Analysis
3. Model Training
4. Model Evaluation
5. Feature Importance Analysis

---

## 💡 Key Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Binary Classification
- Logistic Regression
- Random Forest
- LightGBM
- XGBoost
- Hyperparameter Tuning
- Model Evaluation
- ROC Analysis
- SHAP Explainability
- Feature Importance Analysis
- Healthcare Data Analytics

---

## 🌍 Applications

- Public Health Analytics
- Family Planning Programs
- Healthcare Decision Support
- Population Health Research
- Government Policy Planning
- Women's Reproductive Health Services

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- End-to-end machine learning workflow
- Healthcare data analysis
- Handling imbalanced classification problems
- Comparing multiple classification algorithms
- Model evaluation using multiple performance metrics
- Model interpretability with SHAP
- Translating machine learning results into actionable policy insights

---
