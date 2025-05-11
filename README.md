Car Price Prediction Project
This project is based on the Car Price Prediction case study from the Machine Learning Bookcamp by Alexey Grigorev. The goal is to build a machine learning model that predicts the selling price of used cars based on various features like make, model, year, mileage, and more.

🛠 Project Overview
We follow a complete ML workflow:

Data Loading & Exploration: Load and understand the dataset (EDA)

Data Cleaning: Handle missing values and incorrect data entries

Feature Engineering: Convert categorical variables using one-hot encoding and log-transform skewed features

Model Training: Use linear regression and XGBoost models

Model Evaluation: Measure performance using RMSE (Root Mean Squared Error)

📊 Dataset: https://www.kaggle.com/datasets/CooperUnion/cardataset
The dataset includes details like:

Car make and mode

Year of manufacture

Mileage

Transmission type

Engine size

Fuel type

Tax and MPG

🧠 Machine Learning Models
Two models are trained and evaluated:

Linear Regression: Baseline model for interpretability

XGBoost: Gradient boosting model for improved performance

Hyperparameters are tuned using cross-validation for best results.

⚙️ Tools & Libraries
Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib, Seaborn

📈 Results
The final model achieves strong predictive accuracy, making it useful for estimating used car prices in a real-world application.
