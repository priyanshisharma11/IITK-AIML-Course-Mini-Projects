# IMDB Movie Review Sentiment Analysis using Artificial Neural Network (ANN)

## Objective
Build an Artificial Neural Network (ANN) to classify IMDB movie reviews as either positive or negative using text data.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Dataset
- **Dataset:** IMDB Movie Reviews (built-in from Keras)
- **Training Reviews:** 25,000
- **Testing Reviews:** 25,000
- **Vocabulary Size:** 10,000 most frequent words

## Problem Statement
The objective is to perform binary sentiment classification by predicting whether a movie review expresses a positive or negative opinion.

## Model Architecture
- Input Layer (10,000 features)
- Dense Layer (50 neurons, ReLU)
- Dense Layer (50 neurons, ReLU)
- Dense Layer (50 neurons, ReLU)
- Output Layer (1 neuron, Sigmoid)

## Workflow
1. Load the IMDB movie review dataset.
2. Convert text sequences into binary vector representations.
3. Build a feedforward Artificial Neural Network (ANN).
4. Train the model using Binary Crossentropy loss and Adam optimizer.
5. Predict sentiments for the test dataset.
6. Evaluate the model using Accuracy Score and Confusion Matrix.
7. Visualize training and validation performance.

## Results / Output
The program displays:
- Training Loss vs Epochs
- Training Accuracy vs Epochs
- Validation Loss vs Epochs
- Validation Accuracy vs Epochs
- Confusion Matrix
- Sentiment Classification Accuracy

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials and implementation guidance were provided for educational purposes.
