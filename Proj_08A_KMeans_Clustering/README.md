# K-Means Clustering

## Objective
Apply the K-Means clustering algorithm to group synthetic data points into clusters and evaluate the optimal number of clusters using the Elbow Method and Silhouette Score.

## Technologies Used
- Python
- Scikit-learn
- Matplotlib

## Dataset
- **Dataset:** Synthetic dataset generated using `make_blobs()` from Scikit-learn.
- **Number of Samples:** 2500
- **Number of Features:** 2
- **Number of Clusters:** 4

## Workflow
1. Generate a synthetic dataset using `make_blobs()`.
2. Apply the K-Means clustering algorithm.
3. Visualize the clustered data.
4. Use the Elbow Method to analyze the Sum of Squared Errors (SSE).
5. Use the Silhouette Score to evaluate clustering quality.

## Results / Output
The program displays:
- Original generated dataset
- Clustered data using K-Means
- Elbow Method (SSE) plot
- Silhouette Score plot

## Acknowledgement
This mini-project was completed as part of the IIT Kanpur AI/ML Workshop through guided learning. Course materials and implementation guidance were provided for educational purposes.
