# California Housing Price Prediction using Artificial Neural Network (ANN)

## Objective
Build an Artificial Neural Network (ANN) model to predict California housing prices using housing-related features.

## Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

## Dataset
- **Dataset:** California Housing Dataset (built-in from Scikit-learn)
- **Number of Samples:** 20,640
- **Input Features:**
  - MedInc
  - HouseAge
  - AveRooms
  - AveBedrms
  - Population
  - AveOccup
  - Latitude
  - Longitude
- **Target Variable:**
  - MedHouseVal (Median House Value)

## Neural Network Architecture
- Input Layer: 8 features
- Hidden Layer: 8 neurons (ReLU)
- Output Layer: 1 neuron (Regression)

## Workflow
1. Load the California Housing dataset.
2. Standardize the input features.
3. Split the dataset into training and testing sets.
4. Build an Artificial Neural Network (ANN).
5. Train the model using the Adam optimizer.
6. Predict house prices on the test dataset.
7. Evaluate the model using Mean Squared Error (MSE) and R² Score.
8. Plot the training loss over epochs.

## Results / Output
The program displays:
- Test Mean Squared Error (MSE)
- Test R² Score
- Training Loss vs Epochs graph

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials, datasets, and implementation guidance were provided for educational purposes.
