Stroke Prediction – Machine Learning Approach
📋 About the Project
Every year, around 12.2 million new stroke cases occur worldwide, with 6.5 million resulting in death. The remaining 5.7 million survivors face a long and difficult journey to regain the ability to walk, speak, and carry out daily activities.

This project uses data visualization and machine learning techniques to identify the key factors that contribute to stroke risk and to predict the likelihood of future stroke occurrences.

🎯 Objectives
Analyze the relationships between healthy and unhealthy lifestyle habits

Identify the most influential variables in stroke risk

Select the best-performing machine learning model and apply hyperparameter tuning

📂 Table of Contents
Introduction

Project overview

Libraries and tools used

Data loading, missing value handling, and feature engineering

Exploratory Data Analysis (EDA)

Target variable distribution

Univariate analysis of continuous and categorical variables

Correlation visualizations between features

Data Balancing and Sampling Techniques

Modeling and Results

🛠 Technologies Used
Python

Pandas, NumPy – data processing

Matplotlib, Seaborn, Plotly – data visualization

Scikit-learn – modeling and evaluation

SMOTE – handling data imbalance

📊 Modeling Workflow
Data preprocessing (missing value imputation, encoding, normalization)

Addressing class imbalance with oversampling/undersampling techniques

Training multiple models (Logistic Regression, Random Forest, XGBoost, etc.)

GridSearchCV for hyperparameter optimization

Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

🚀 How to Run
bash
Kopyala
Düzenle
# 1. Install required libraries
pip install -r requirements.txt

# 2. Run the notebook
jupyter notebook "StrokePrediction.ipynb"
📈 Results
The best model was achieved using algorithm X with hyperparameters Y, reaching a ROC-AUC score of 0.XX.
This model can be a valuable tool for understanding stroke risk factors and supporting preventive healthcare strategies.


