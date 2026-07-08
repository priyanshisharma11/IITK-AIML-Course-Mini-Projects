# Car Purchase Prediction using Naive Bayes

## Objective
Build a Naive Bayes classifier to predict whether a customer is likely to purchase a new car based on age and estimated salary.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Dataset
- **Dataset:** Purchase_Logistic.csv
- **Input Features:**
  - Age
  - Estimated Salary
- **Target Variable:**
  - Purchased (1 = Yes, 0 = No)

## Workflow
1. Load the customer purchase dataset.
2. Select age and estimated salary as input features.
3. Standardize the feature values.
4. Split the dataset into training and testing sets.
5. Train a Gaussian Naive Bayes classifier.
6. Predict customer purchase decisions.
7. Evaluate the model using a Confusion Matrix and Accuracy Score.
8. Visualize the original dataset and the classification results.

## Results / Output
The program displays:
- Scatter plot of the original dataset
- Scatter plot showing Naive Bayes predictions
- Confusion Matrix
- Classification Accuracy Score

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials, datasets, and implementation guidance were provided for educational purposes.
