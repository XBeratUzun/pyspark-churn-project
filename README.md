Customer Churn Prediction with PySpark

This project predicts customer churn using the Telco Customer Churn dataset and PySpark. All steps are performed in a single notebook named churn_etl_project.ipynb.

The notebook includes:
- Loading and cleaning the dataset
- Handling missing values and type conversions
- Encoding categorical variables using StringIndexer
- Assembling features into a single vector column
- Training a logistic regression model using PySpark MLlib
- Evaluating the model using AUC (Area Under ROC Curve)