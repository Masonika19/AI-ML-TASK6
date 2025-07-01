# AI-ML-TASK6
#KNN Classification on Iris Dataset

To classify Iris flowers into species (Setosa, Versicolor, Virginica) using the K-Nearest Neighbors (KNN) algorithm and visualize decision boundaries.
Loaded Iris.csv using Pandas and dropped the Id column as it's not useful for classification.
Label Encoding : Converted the Species column to numeric values (0, 1, 2).
Feature Scaling: Used MinMaxScaler to normalize feature values between 0 and 1 (important for distance-based KNN).
Train-Test Split: Split the dataset into training and testing sets (50% test size for evaluation).
KNN Model Training: Trained KNN classifiers for K values from 1 to 20 and calculated and plotted accuracy for each K to find the best K.
Selected the best K and evaluated the model using:
Accuracy
Confusion Matrix
Classification Report
Decision Boundary Visualization: Used only two features (PetalLengthCm, PetalWidthCm) to visualize the decision boundaries of the KNN model in 2D space.
The Accuracy it shows  is 98.67%( when test size is 0.5)
#Output is Best K: 1
This means the best value of K (number of neighbors) found during training is 1 — meaning the model makes its prediction based on just the single closest data point.
