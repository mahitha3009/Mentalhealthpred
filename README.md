**Mental Health Prediction in the Corporate World**

**Overview**
This project aims to analyze and predict mental health challenges in corporate environments using machine learning models. It leverages logistic regression, support vector machines, decision trees, random forests, XGBoost, and neural networks to determine whether an employee is likely to seek mental health treatment based on workplace conditions and personal factors.

**Problem Statement**
With increasing workplace stress, anxiety, and depression, mental health has become a crucial issue in corporate settings. This project explores:

The impact of workplace factors on mental health.
The effectiveness of employer-provided mental health resources.
Predicting if an employee will seek mental health treatment based on company benefits and policies.
Data Source
The dataset is sourced from Open Sourcing Mental Illness, containing 4000+ records and 18 features, including age, gender, employment type, workplace policies, and access to mental health resources.
📂 Dataset Link:  https://github.com/ronitrex/MentalHealth/tree/master/datasets

**Technologies Used**
Programming Languages: Python
Libraries & Frameworks: NumPy, Pandas, Scikit-Learn, PyTorch
Models Implemented
Logistic Regression
Support Vector Machines (SVM)
Decision Tree
Random Forest
XGBoost
Neural Networks
Voting Classifier (with PCA)
Visualization & Analysis: Matplotlib, Seaborn
Database: PostgreSQL
Version Control: Git & GitHub
Data Preprocessing Steps
Cleaning and transforming raw data.
Handling missing values, outliers, and categorical encoding.
Exploratory Data Analysis (EDA) using visualizations to find patterns in mental health challenges.
Model Performance
The best-performing model was the Voting Classifier (with PCA), achieving:

Accuracy: 60%
Precision: 59.7%
Recall: 93%
F1 Score: 72.7%
This model effectively balances recall and precision, making it a reliable choice for predicting mental health treatment decisions.

Future Improvements
-------------------
Implementing deep learning models for higher accuracy.
Enhancing feature engineering techniques.
Addressing class imbalance issues to improve precision.
