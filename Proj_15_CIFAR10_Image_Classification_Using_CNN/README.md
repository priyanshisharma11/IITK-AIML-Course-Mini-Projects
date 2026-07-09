# CIFAR-10 Image Classification using Convolutional Neural Network (CNN)

## Objective
Build a Convolutional Neural Network (CNN) to classify color images from the CIFAR-10 dataset into one of ten object categories.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Dataset
- **Dataset:** CIFAR-10 (built-in from Keras)
- **Training Images:** 50,000
- **Testing Images:** 10,000
- **Image Size:** 32 × 32 pixels (RGB Color)

## Classes

| Label | Class |
|------|-----------|
| 0 | Airplane |
| 1 | Automobile |
| 2 | Bird |
| 3 | Cat |
| 4 | Deer |
| 5 | Dog |
| 6 | Frog |
| 7 | Horse |
| 8 | Ship |
| 9 | Truck |

## CNN Architecture
- Input Layer (32 × 32 × 3)
- Convolution Layer (32 filters, ReLU)
- Batch Normalization
- Convolution Layer (32 filters, ReLU)
- Batch Normalization
- Max Pooling Layer
- Dropout (0.3)

- Convolution Layer (64 filters, ReLU)
- Batch Normalization
- Convolution Layer (64 filters, ReLU)
- Batch Normalization
- Max Pooling Layer
- Dropout (0.5)

- Convolution Layer (128 filters, ReLU)
- Batch Normalization
- Convolution Layer (128 filters, ReLU)
- Batch Normalization
- Max Pooling Layer
- Dropout (0.5)

- Flatten Layer
- Dense Layer (128 neurons, ReLU)
- Batch Normalization
- Dropout (0.5)
- Output Layer (10 neurons, Softmax)

## Workflow
1. Load the CIFAR-10 dataset.
2. Display sample images from different object categories.
3. Normalize pixel values.
4. Build a deep CNN using convolution, pooling, batch normalization, and dropout layers.
5. Train the model using the Adam optimizer.
6. Predict image classes on the test dataset.
7. Evaluate the model using Accuracy Score and Confusion Matrix.
8. Visualize training and validation performance.

## Results / Output
The program displays:
- Sample CIFAR-10 images
- Training Loss vs Epochs
- Training Accuracy vs Epochs
- Validation Loss vs Epochs
- Validation Accuracy vs Epochs
- Confusion Matrix
- Classification Accuracy Score

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials and implementation guidance were provided for educational purposes.
