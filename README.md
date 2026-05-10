# Student Performance Prediction using Machine Learning

---

## 📌 Project Overview

This project implements a complete Machine Learning pipeline to predict student academic grades using supervised classification techniques. The goal is to analyze student-related attributes and classify final grades (A, B, C, D, F) using predictive modeling.

The project demonstrates data preprocessing, feature engineering, model training, evaluation, and model persistence.

---

## 🎯 Problem Statement

Given student performance data, predict the final grade category using machine learning classification models.

This is a **multi-class classification problem**.

Target Variable:
- `grade`
- Classes: A, B, C, D, F

---

## 📊 Dataset Processing Steps

1. Dataset exploration (shape, columns, data types, missing values)
2. Feature-target separation
3. One-hot encoding of categorical features using `pd.get_dummies()`
4. Train-test split (80% training, 20% testing)
5. Feature scaling using `StandardScaler`
6. Model training and evaluation

---

## ⚙️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

Key sklearn modules:
- LogisticRegression
- RandomForestClassifier
- train_test_split
- StandardScaler
- accuracy_score
- classification_report
- confusion_matrix

---

## 📌 Conclusion

This project successfully demonstrates a full machine learning classification workflow, from raw data preprocessing to model training and prediction export. Random Forest provided robust performance for multi-class grade prediction.

The project highlights the importance of preprocessing, encoding, and proper train-test splitting in achieving reliable predictive results.

---

## 👨‍💻 Author

Name: Muhammad Mohsin Nehan  
