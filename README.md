# Bank Customer Churn Analysis

This project aims to analyze a bank's customer churn dataset (Kaggle BankChurners) and develop models to predict customer attrition. The analysis starts with data exploration, visualization, and preprocessing steps, followed by model selection and evaluation.

## Data Exploration
The dataset contains information about bank customers, including their demographics, account details, and churn status. The analysis begins with an overview of the data distribution through various visualizations:

Customer age distribution
Gender distribution
Dependent count distribution
Education level distribution
Marital status distribution
Income category distribution
Card category distribution
Months on book distribution
Total relationship count distribution
Months inactive in the last 12 months distribution
Credit limit distribution
Total transaction amount distribution
Churn vs. non-churn customer proportion
Data Preprocessing

The following preprocessing steps are performed:

One-hot encoding of categorical features
Upsampling the data using SMOTE to handle the imbalanced class distribution
Dimensionality reduction of one-hot encoded features using Principal Component Analysis (PCA)
Model Selection and Evaluation
Two classification models, Random Forest and Support Vector Machine (SVM), are evaluated using 5-fold cross-validation. Their performance is assessed using the F1 score.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Authors: Bohdan Boiprav & Catalin Bondari