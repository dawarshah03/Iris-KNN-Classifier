# Iris-KNN-Classifier

## Problem
We want to classify different types of Iris flowers based on their features. The goal is to help machines recognize the type of flower: Setosa, Versicolor, or Virginica.

## Solution
We used the K-Nearest Neighbors (KNN) algorithm. KNN predicts the flower type by looking at nearby data points and choosing the most common one.

## What Are We Finding
We are trying to predict the correct flower class based on its numeric input values using KNN classification.

## Columns Used
We used the built-in Iris dataset from sklearn. It contains:

- sepal length (cm)
- sepal width (cm)
- petal length (cm)
- petal width (cm)

target (0 = Setosa, 1 = Versicolor, 2 = Virginica)

## Accuracy & Results
Our model reached an accuracy of 96.67% (0.9667).
It means the model correctly predicted most flower types in the test data.

## Confusion Matrix
We also used a confusion matrix for a better understanding of predictions.
