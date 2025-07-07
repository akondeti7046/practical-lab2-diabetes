# Practical Lab 2 – Predicting Diabetes Progression using Machine Learning

## 🔍 Objective

This lab explores the **Scikit-learn Diabetes dataset** to predict the risk of diabetes progression. The aim is to build and compare different machine learning models to identify the most effective one for predicting disease progression one year after baseline.

## 📁 Dataset

- **Source**: `sklearn.datasets.load_diabetes()`
- The dataset consists of 442 samples and 10 input features (normalized).
- Target variable: a quantitative measure of disease progression after one year.

## 🧪 Models Implemented

### 🧵 Univariate Polynomial Regression
- Feature: BMI
- Degrees: 0 to 5
- Evaluated using: R², MAE, MAPE
- Best: Degree 5 (test R² ≈ 0.27)

### 🔢 Multivariate Polynomial Regression
- Degrees: 2 and 3
- Observed overfitting and instability

### 🌲 Decision Tree Regression
- Depths: 3 and 5
- Best validation R² at depth 3

### 👥 k-Nearest Neighbors (kNN)
- Values: k=3, k=5
- Best performance with k=5 (Val R² ≈ 0.36)

## 📊 Evaluation Metrics
- R² (R-squared)
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)

## 🔍 Key Insights
- BMI alone is insufficient to explain most variance in diabetes progression.
- kNN with k=5 generalized better than other models.
- Feature interactions may be complex; further feature engineering and advanced models are recommended.

## 📝 Files Included
- `Practical Lab 2.ipynb`: Jupyter notebook with all code, models, and results.
- `requirements.txt`: Python dependencies for reproducibility.
- `README.md`: This project overview.

## 🧠 Future Improvements
- Add cross-validation for more robust model evaluation.
- Experiment with ensemble methods (Random Forest, Gradient Boosting).
- Perform hyperparameter tuning.

## 📌 Author
**Adhitya Kondeti**  
Student ID: 8997046  
Conestoga College – Artificial Intelligence and Machine Learning
This is a new line added directly via terminal at Mon Jul  7 14:44:09 EDT 2025
