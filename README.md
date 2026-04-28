# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview
This project predicts whether a customer will **churn (leave)** or **stay** using machine learning techniques.  
The goal is to help businesses identify at-risk customers and take proactive retention actions.

---

## 🎯 Objective
- Build a machine learning model to predict customer churn  
- Improve prediction accuracy using preprocessing and feature engineering  
- Analyze key factors influencing customer churn  
- Compare multiple models for better performance  

---

## 📁 Dataset
- Dataset: Telco Customer Churn Dataset  
- Source: Kaggle  
- Contains customer demographics, account information, and service usage details  

---

## 🛠️ Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Removed irrelevant columns (e.g., customerID)  
- Converted target variable (Yes/No → 1/0)  
- Handled missing values  
- Applied one-hot encoding for categorical variables  

### 2. Feature Engineering
- Transformed categorical features into numerical format  
- Scaled features using StandardScaler  

### 3. Model Building
- Logistic Regression (baseline model)  
- Random Forest Classifier (improved model)  

### 4. Model Evaluation
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-score  

### 5. Visualization
- Confusion matrix heatmap  
- Feature importance chart  

---

## 📊 Results
- Logistic Regression Accuracy: *[add your value]*  
- Random Forest Accuracy: *[add your value]*  
- Random Forest performed better due to handling complex patterns  

---

## 📈 Key Insights
- Contract type is a major factor in customer churn  
- Monthly charges influence churn probability  
- Tenure is strongly related to customer retention  

---
