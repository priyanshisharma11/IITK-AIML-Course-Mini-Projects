# Boston Housing Price Prediction using Artificial Neural Network (ANN)

## Objective
Build an Artificial Neural Network (ANN) model to predict Boston housing prices using multiple housing-related features.

## Technologies Used
- Python
- Pandas
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

## Dataset
- **Dataset:** BostonHousing.csv
- **Input Features (11):**
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
- **Target Variable:**
  - MEDV (Median value of owner-occupied homes in $1000s)

## Neural Network Architecture
- Input Layer: 11 features
- Hidden Layer 1: 128 neurons (ReLU)
- Hidden Layer 2: 64 neurons (ReLU)
- Hidden Layer 3: 32 neurons (ReLU)
- Output Layer: 1 neuron (Regression)

## Workflow
1. Load the Boston Housing dataset.
2. Standardize the input features.
3. Split the dataset into training and testing sets.
4. Build an ANN using TensorFlow/Keras.
5. Train the model using the Adam optimizer.
6. Predict housing prices on the test dataset.
7. Evaluate the model using Mean Squared Error (MSE) and R² Score.
8. Plot the training loss over epochs.

## Results / Output
The program displays:
- Test Mean Squared Error (MSE)
- Test R² Score
- Training Loss vs Epochs graph

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials, datasets, and implementation guidance were provided for educational purposes.
