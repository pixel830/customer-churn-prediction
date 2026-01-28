# Customer Churn Prediction

This project builds an end-to-end machine learning solution to predict customer churn using telecom customer data.  
The goal is to identify customers who are likely to leave a service so that businesses can take proactive retention actions.

## Project Overview

Customer churn is a critical problem for subscription-based businesses.  
In this project, I analyzed customer behavior data, performed feature engineering, and trained a classification model to predict churn.

The focus was not only on model accuracy, but also on understanding **which factors contribute most to customer churn**.

## What This Project Covers

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature engineering
- Handling categorical variables
- Training and evaluating a classification model
- Saving the trained model for future use

## Tech Stack

- Python  
- pandas, NumPy  
- scikit-learn  
- Jupyter Notebook  

## Files in This Repository

- `Customer_churn_prediction.ipynb`  
  Main notebook containing data analysis, model training, and evaluation.

- `churn_model.pkl`  
  Trained machine learning model saved for reuse.

- `.gitignore`  
  Ensures large and unnecessary files are excluded from version control.

## Note on Dataset

Large processed datasets are excluded from this repository due to GitHub file size limits.  
All steps to clean, preprocess, and regenerate the data are included inside the notebook.


## Future Improvements

- Deploy the model using a Flask or FastAPI backend
- Build a simple web interface for predictions
- Add model monitoring and performance tracking
- Experiment with advanced models and hyperparameter tuning

## Author

Developed as a hands-on machine learning project to demonstrate real-world ML workflows, version control practices, and problem-solving skills.
