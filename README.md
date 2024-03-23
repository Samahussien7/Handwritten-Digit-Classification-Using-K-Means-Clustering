# Handwritten-Digit-Classification-Using-K-Means-Clustering
Using K-Means clustering, with feature extraction comparison between centroid and chaincode methods.. The script implements K-Means clustering from scratch, performs feature extraction using both centroid and chaincode techniques, evaluates classification accuracy, and compares the effectiveness of the two feature extraction methods.

# Steps:

## Load MNIST Dataset:
Retrieves the MNIST dataset containing images of handwritten digits along with their corresponding labels.

## Feature Extraction with Centroid Method:
Computes centroids for each image.
Uses centroid coordinates as features for clustering.

## K-Means Clustering:
Implements K-Means clustering algorithm without relying on built-in functions.
Clusters the data based on the extracted centroid features.

## Classification and Accuracy Evaluation (Centroid Method):
Assigns cluster labels to each image and evaluates classification accuracy.
Computes accuracy metric to assess the performance of K-Means clustering with centroid feature extraction.

## Feature Extraction with Chaincode Method:
Computes chaincode for each image block.
Utilizes chaincode features for clustering.

## K-Means Clustering (Chaincode Method):
Applies K-Means clustering using chaincode features.

## Classification and Accuracy Evaluation (Chaincode Method):
Assigns cluster labels to images based on chaincode features and evaluates accuracy.
Computes accuracy metric to compare with the centroid method.

## Comparison of Feature Extraction Methods:
Analyzes and compares the accuracy achieved with centroid and chaincode feature extraction.
Determines which feature extraction method yields better performance with K-Means clustering.
