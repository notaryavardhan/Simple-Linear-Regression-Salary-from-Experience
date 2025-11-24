# Simple Linear Regression (Salary Prediction)

This project implements a Simple Linear Regression model using Python and scikit-learn to predict an employee's salary based on their years of experience. This is a foundational machine learning exercise demonstrating data preprocessing, model training, and result visualization.

## 🛠️ Prerequisites

Required Python libraries:
scikit-learn is required for this to work, it can be installed using the command
pip install numpy matplotlib pandas scikit-learn

## How to run
Ensure the Salary_Data.csv file is in the same directory as the Python script
Run the script from your terminal

## Data & Model Notes
Input: Years of Experience (Independent variable, X).
Output: Salary (Dependent variable, y).
Model: sklearn.linear_model.LinearRegression.
Preprocessing: Both X and y are subjected to Feature Scaling using StandardScaler prior to model fitting to standardize their ranges.
