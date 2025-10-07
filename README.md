# 🚢 Titanic Survival Prediction

A classic data science project predicting whether a passenger survived the Titanic disaster using Python and machine learning.  
This notebook walks through the complete data science workflow — from data cleaning and feature engineering to model training and evaluation.

---

## 🧠 Project Overview

This project explores the **Titanic dataset** to predict survival using a range of supervised learning algorithms.

### Key Steps:
1. **Data Loading & Cleaning**  
   - Handle missing values  
   - Extract titles and family information  
   - Encode categorical features  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize survival distribution by gender, class, and age  
   - Understand correlations between key variables  

3. **Feature Engineering**  
   - Create meaningful new features (e.g., family size, title encoding)  
   - Scale numeric data for model training  

4. **Model Training & Evaluation**  
   - Compare multiple models: Logistic Regression, Random Forest, SVM, XGBoost, MLP, etc.  
   - Use cross-validation for fair model comparison  
   - Evaluate accuracy and F1-score  

5. **Feature Importance Analysis**  
   - Identify which factors most influenced survival  

---

## 🧩 Models Used

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Classifier (SVC)  
- AdaBoost Classifier  
- Gradient Boosting Classifier  
- XGBoost Classifier  
- Multi-layer Perceptron (Neural Network)

---

## 📊 Results Summary

| Model | Accuracy | F1 Score |
|:------|:----------|:---------|
| RandomForestClassifier | 0.82 | 0.79 |
| LogisticRegression | 0.80 | 0.78 |
| XGBClassifier | 0.83 | 0.80 |

---

