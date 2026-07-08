# Breast Cancer Classification using Support Vector Machine (SVM)

## Objective
Build and compare Support Vector Machine (SVM) classifiers with different kernels to classify breast cancer tumors as benign or malignant.

## Technologies Used
- Python
- Scikit-learn
- Matplotlib

## Dataset
- **Dataset:** Breast Cancer Wisconsin (Diagnostic) Dataset (built-in from Scikit-learn)
- **Input Features:** 30 diagnostic features
- **Target Variable:**
  - 0 = Malignant
  - 1 = Benign

## Models Used
- Linear SVM
- SVM with RBF (Gaussian) Kernel
- SVM with Polynomial Kernel
- SVM with Sigmoid Kernel

## Workflow
1. Load the Breast Cancer dataset.
2. Standardize the input features.
3. Split the dataset into training and testing sets.
4. Train SVM classifiers using different kernels.
5. Predict tumor classes on the test dataset.
6. Evaluate each model using Accuracy Score and Confusion Matrix.
7. Compare the performance of different SVM kernels.

## Results / Output
The program displays:
- Accuracy Score for each SVM kernel
- Confusion Matrix for each SVM kernel
- Performance comparison of:
  - Linear Kernel
  - RBF Kernel
  - Polynomial Kernel
  - Sigmoid Kernel

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials, datasets, and implementation guidance were provided for educational purposes.
