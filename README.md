# Customer Churn Prediction using Machine Learning and Artificial Neural Networks

## 📌 Project Overview

Customer churn prediction is a critical business problem that helps organizations identify customers who are likely to discontinue their services. In this project, multiple Machine Learning models and an Artificial Neural Network (ANN) were developed and compared to predict customer churn.

The project includes data preprocessing, feature scaling, handling class imbalance using SMOTE, model training, and performance evaluation.

---

## 🎯 Problem Statement

The objective of this project is to predict whether a customer will churn based on customer demographics, account information, and service usage patterns.

Early identification of potential churners enables businesses to implement targeted retention strategies and reduce customer attrition.

---

## 📊 Dataset Features

The dataset contains customer-related information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges

### Target Variable

- **0 → Customer Retained**
- **1 → Customer Churned**

---

## ⚙️ Project Workflow

### Data Preprocessing

- Handled missing values
- Label Encoding & One-Hot Encoding
- Train, Validation and Test Split
- Feature Scaling using StandardScaler

### Class Imbalance Handling

Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance the minority class.

### Models Implemented

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- Artificial Neural Network (ANN)


---

## 📈 Model Performance

### Logistic Regression

| Metric | Class 0 | Class 1 |
|----------|----------|----------|
| Precision | 0.86 | 0.58 |
| Recall | 0.85 | 0.59 |
| F1-Score | 0.85 | 0.59 |

**Accuracy:** 78%

---

### Random Forest

| Metric | Class 0 | Class 1 |
|----------|----------|----------|
| Precision | 0.84 | 0.56 |
| Recall | 0.86 | 0.52 |
| F1-Score | 0.85 | 0.54 |

**Accuracy:** 77%

---

### XGBoost

| Metric | Class 0 | Class 1 |
|----------|----------|----------|
| Precision | 0.83 | 0.53 |
| Recall | 0.85 | 0.51 |
| F1-Score | 0.84 | 0.52 |

**Accuracy:** 76%

---

### Artificial Neural Network (ANN)

| Metric | Class 0 | Class 1 |
|----------|----------|----------|
| Precision | 0.86 | 0.59 |
| Recall | 0.86 | 0.59 |
| F1-Score | 0.86 | 0.59 |

**Accuracy:** 79%

**ROC-AUC Score:** 0.817

---

## 🔍 Key Findings

- ANN achieved the highest overall performance among all tested models.
- Logistic Regression also produced competitive results.
- SMOTE improved the detection of churning customers.
- ANN provided the best balance between precision and recall.
- ROC-AUC score of 0.817 indicates good class-separation capability.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow / Keras
- XGBoost
- Imbalanced-Learn (SMOTE)
- Matplotlib
- Seaborn

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Feature engineering
- Threshold optimization
- Ensemble learning techniques
- Model deployment using Streamlit
- Explainable AI using SHAP values

---

## 📌 Conclusion

This project demonstrates the application of Machine Learning and Deep Learning techniques to solve a real-world customer churn prediction problem. Among all the implemented models, the Artificial Neural Network achieved the best performance with an accuracy of **79%** and a **ROC-AUC score of 0.817**, making it the most effective model for identifying customers at risk of churn.

---

