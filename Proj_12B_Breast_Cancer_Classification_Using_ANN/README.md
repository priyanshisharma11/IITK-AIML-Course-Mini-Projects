# Breast Cancer Classification using Artificial Neural Network (ANN)

## Objective
Develop an Artificial Neural Network (ANN) to classify breast cancer tumors as benign or malignant using diagnostic features from the Breast Cancer Wisconsin dataset.

## Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Matplotlib

## Dataset
- **Dataset:** Breast Cancer Wisconsin (Diagnostic) Dataset (built-in from Scikit-learn)
- **Number of Samples:** 569
- **Number of Features:** 30

### Target Classes
- 0 = Malignant
- 1 = Benign

## Neural Network Architecture
- Input Layer: 30 features
- Hidden Layer 1: 64 neurons (ReLU)
- Dropout (0.5)
- Hidden Layer 2: 128 neurons (ReLU)
- Dropout (0.5)
- Hidden Layer 3: 32 neurons (ReLU)
- Dropout (0.5)
- Hidden Layer 4: 16 neurons (ReLU)
- Dropout (0.5)
- Output Layer: 2 neurons (Softmax)

## Workflow
1. Load the Breast Cancer Wisconsin dataset.
2. Standardize the input features.
3. Split the dataset into training and testing sets.
4. Apply One-Hot Encoding to the target labels.
5. Build an Artificial Neural Network (ANN).
6. Train the model using categorical cross-entropy loss and the Adam optimizer.
7. Predict tumor classes on the test dataset.
8. Evaluate the model using Accuracy Score and Confusion Matrix.
9. Visualize training and validation performance.

## Results / Output
The program displays:
- Training Loss vs Epochs
- Training Accuracy vs Epochs
- Validation Loss vs Epochs
- Validation Accuracy vs Epochs
- Confusion Matrix
- Classification Accuracy Score

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials, datasets, and implementation guidance were provided for educational purposes.
