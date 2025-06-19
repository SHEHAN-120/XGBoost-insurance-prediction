💡 XGBoost Regression on Medical Insurance Cost Prediction

This project applies XGBoost Regression to predict medical insurance charges based on personal, demographic, and health-related features. It demonstrates how machine learning can model real-world costs and highlight key factors driving insurance pricing.

📊 Dataset Features

The dataset contains the following variables:

🧑‍🦱 Age – Age of the primary beneficiary

🚻 Sex – Gender of the insured individual (male, female)

⚖️ BMI – Body Mass Index

👶 Children – Number of dependents covered by insurance

🚬 Smoker – Smoking status (yes, no)

🌎 Region – Residential area (northeast, southeast, etc.)

💰 Charges – Medical insurance cost (target variable)

🎯 Project Goal

To build a supervised regression model using XGBoost, a powerful and scalable gradient boosting algorithm, in order to:

Accurately predict individual medical insurance costs

Identify the most important features affecting the cost

Demonstrate the effectiveness of XGBoost in small structured datasets

🔍 Key Steps in This Project

✅ Data Preprocessing
    – Encoding categorical variables (like sex, region, smoker)
    – Checking for missing values and data types

✅ Feature Scaling (if needed)
    – Apply standardization or normalization if model requires it

✅ Model Training
    – Using XGBRegressor from the XGBoost library

✅ Model Evaluation
    – R² Score

  Data set ------> 
  https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset

