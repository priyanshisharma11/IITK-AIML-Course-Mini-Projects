# Boston Housing Price Prediction using Linear Regression

## Objective
Build a Linear Regression model to predict the median value of owner-occupied homes (MEDV) using selected housing features from the Boston Housing dataset.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Dataset
- **Dataset:** Boston Housing Dataset (`BostonHousing.csv`)
- **Target Variable:** MEDV (Median value of owner-occupied homes in $1000s)

## Features Used
- CRIM
- ZN
- INDUS
- CHAS
- NOX
- RM
- AGE
- DIS
- RAD
- TAX
- PTRATIO

## Workflow
1. Load the Boston Housing dataset.
2. Select input features and target variable.
3. Split the dataset into training and testing sets.
4. Train a Linear Regression model.
5. Evaluate the model using:
   - Mean Squared Error (MSE)
   - R² Score
6. Visualize Actual vs Predicted house prices.

## Output
The project displays:
- Training MSE and R² Score
- Testing MSE and R² Score
- Scatter plot comparing Actual and Predicted house prices

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials, datasets, and implementation guidance were provided for educational purposes.
