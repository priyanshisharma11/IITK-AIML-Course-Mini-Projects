# Handwritten Digit Recognition using Convolutional Neural Network (CNN)

## Objective
Build a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) using the MNIST dataset.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Dataset
- **Dataset:** MNIST (built-in from Keras)
- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28 pixels (Grayscale)

## Classes
The dataset contains handwritten digits:
- 0
- 1
- 2
- 3
- 4
- 5
- 6
- 7
- 8
- 9

## CNN Architecture
- Input Layer (28 × 28 × 1)
- Convolution Layer (64 filters, ReLU)
- Convolution Layer (32 filters, ReLU)
- Flatten Layer
- Output Layer (10 neurons, Softmax)

## Workflow
1. Load the MNIST handwritten digit dataset.
2. Display sample handwritten digit images.
3. Reshape images for CNN input.
4. Apply One-Hot Encoding to target labels.
5. Build a CNN model.
6. Train the model using the Adam optimizer.
7. Predict handwritten digit classes.
8. Evaluate the model using Accuracy Score and Confusion Matrix.
9. Visualize training and validation performance.

## Results / Output
The program displays:
- Sample handwritten digit images
- Training Loss vs Epochs
- Training Accuracy vs Epochs
- Validation Loss vs Epochs
- Validation Accuracy vs Epochs
- Confusion Matrix
- Classification Accuracy Score

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials and implementation guidance were provided for educational purposes.
