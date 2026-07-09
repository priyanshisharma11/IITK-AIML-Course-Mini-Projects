# Fashion MNIST Image Classification using Convolutional Neural Network (CNN)

## Objective
Build a Convolutional Neural Network (CNN) to classify grayscale images of fashion products into one of ten clothing categories.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Dataset
- **Dataset:** Fashion MNIST (built-in from Keras)
- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28 pixels (Grayscale)

## Classes
| Label | Class |
|-------|----------------|
| 0 | T-shirt / Top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle Boot |

## CNN Architecture
- Input Layer (28 × 28 × 1)
- Convolution Layer (64 filters, ReLU)
- Max Pooling Layer
- Convolution Layer (128 filters, ReLU)
- Max Pooling Layer
- Convolution Layer (256 filters, ReLU)
- Max Pooling Layer
- Flatten Layer
- Dense Layer (256 neurons, ReLU)
- Output Layer (10 neurons, Softmax)

## Workflow
1. Load the Fashion MNIST dataset.
2. Display sample fashion images.
3. Normalize image pixel values.
4. Build a CNN model using convolution and pooling layers.
5. Train the model using the Adam optimizer.
6. Predict image classes.
7. Evaluate the model using Accuracy Score and Confusion Matrix.
8. Visualize training and validation performance.

## Results / Output
The program displays:
- Sample Fashion MNIST images
- Training Loss vs Epochs
- Training Accuracy vs Epochs
- Validation Loss vs Epochs
- Validation Accuracy vs Epochs
- Confusion Matrix
- Classification Accuracy Score

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials and implementation guidance were provided for educational purposes.
