# churn-prediction
Churn prediction model - Machine Learning

Project Summary
This project predicts customer churn using machine learning models on the Telco Customer Churn dataset.

Model Selection

Logistic Regression: Chosen for its interpretability and effectiveness in binary classification tasks.
Random Forest: Selected for its ability to handle complex, non-linear relationships and reduce overfitting through ensemble learning.

Metric Choice

Recall was used as the main evaluation metric.

Pipeline Implementation

- Pipelines were built using scikit-learn and imbalanced-learn to automate preprocessing, feature engineering, and model training.
- Steps included encoding categorical variables, scaling features, handling missing values, and applying SMOTE for class balancing.
- Pipelines ensure reproducibility, prevent data leakage, and simplify model evaluation and comparison.

Process Overview

1. Data Cleaning: Handled missing values and converted categorical features.
2. Feature Engineering: Created new features and scaled numerical columns.
3. Model Training: Trained Logistic Regression and Random Forest models using pipelines.
4. Evaluation: Compared models using F1 Score, accuracy, precision, and recall.
5. Results: Summarized and visualized model performance for easy comparison.
