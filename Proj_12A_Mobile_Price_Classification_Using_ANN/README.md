# Mobile Price Classification using Artificial Neural Network (ANN)

## Objective
Build an Artificial Neural Network (ANN) to classify mobile phones into different price categories based on their specifications.

## Technologies Used
- Python
- Pandas
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- NumPy

## Dataset
- **Dataset:** mobile_prices.csv
- **Number of Input Features:** 20

### Features
- Battery Power
- Bluetooth
- Clock Speed
- Dual SIM
- Front Camera
- 4G Support
- Internal Memory
- Mobile Depth
- Mobile Weight
- Number of CPU Cores
- Primary Camera
- Pixel Height
- Pixel Width
- RAM
- Screen Height
- Screen Width
- Talk Time
- 3G Support
- Touch Screen
- WiFi

### Target Variable
**Price Range**
- 0 = Low Cost
- 1 = Medium Cost
- 2 = High Cost
- 3 = Very High Cost

## Neural Network Architecture
- Input Layer: 20 features
- Hidden Layer 1: 64 neurons (ReLU)
- Dropout (0.5)
- Hidden Layer 2: 128 neurons (ReLU)
- Dropout (0.5)
- Hidden Layer 3: 32 neurons (ReLU)
- Dropout (0.5)
- Hidden Layer 4: 16 neurons (ReLU)
- Dropout (0.5)
- Output Layer: 4 neurons (Softmax)

## Workflow
1. Load the mobile price dataset.
2. Standardize the input features.
3. Split the dataset into training and testing sets.
4. Apply One-Hot Encoding to the target labels.
5. Build an Artificial Neural Network (ANN).
6. Train the model using categorical cross-entropy loss and the Adam optimizer.
7. Predict mobile price categories.
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
