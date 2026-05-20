# Loan Default Prediction System

# 🔹 Overview
This project develops a loan default prediction system using a dataset of 32,587 loan records. The goal is to predict whether a borrower will default, helping financial institutions manage risk.

### 🔹 Dataset
The dataset used in this project contains 32,587 loan records with borrower and loan attributes.  
It is publicly available on Kaggle: [Loan Default Prediction Dataset]([https://www.kaggle.com/your-dataset-link](https://www.kaggle.com/datasets/laotse/credit-risk-dataset))  

Preprocessing steps (missing value imputation, categorical encoding, feature scaling, and SMOTE balancing) are fully documented in the notebook.


# 🔹 Methodology
 - Preprocessing

   Missing value imputation

   Categorical encoding

   Feature scaling

   SMOTE balancing to address class imbalance

- Algorithms Implemented

  Decision Tree

  Random Forest

  K-Nearest Neighbors (KNN)

  Naive Bayes

- Evaluation

  Train-test splits

  K-fold cross-validation

  Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

- Overfitting Analysis

  Training vs. test accuracy comparisons

  Gap visualizations to detect overfitting

# 🔹 Results
The models were compared across multiple metrics to identify the most effective classifier for loan default prediction. Random Forest showed strong performance, but each algorithm’s strengths and weaknesses were analyzed.


