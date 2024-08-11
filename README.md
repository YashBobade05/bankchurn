Bank Churn Prediction Project

Overview This repository contains code and resources related to predicting customer churn in a bank using Support Vector Machines (SVM). The goal is to identify customers who are likely to leave the bank, allowing proactive retention strategies.

Dataset The dataset used for this project includes various features related to bank customers. Some of the key features are: Credit Score: Numeric value representing the creditworthiness of the customer. Geography: Categorical variable indicating the customer's country. Gender: Binary (Male/Female). Tenure: Number of year Age: Age of the customer. Balance: Account balance. Number of Bank Products Used*: How many different bank products the customer uses. Has a Credit Car: Binary (Yes/No). Is an Active Member: Binary (Yes/No). Estimated Salary: Estimated annual salary of the customer. Exited Target variable (1 if the customer left, 0 otherwise).

Approach

Data Preprocessing:
Handle missing values, encode categorical features, and scale numerical features.
Feature Selection:
Identify relevant features using techniques like correlation analysis.
Model Building:
Train an SVM model with an appropriate kernel (e.g., RBF).
Tune hyperparameters (e.g., C and gamma) using cross-validation.
Model Evaluation:
Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.
Deployment:
Deploy the trained model for real-time predictions.
