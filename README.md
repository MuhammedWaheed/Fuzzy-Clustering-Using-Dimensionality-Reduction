# Fuzzy-Clustering-Using-Dimensionality-Reduction
# Dataset:
https://www.kaggle.com/datasets/ouline/student-mat-pass-or-fail

# Problem Statement
This project aims to find out the influence of various variables and parameters on the grade of a secondary school student.
The dataset is extensive with atleast 33 different variables which are then filtered for the most obvious predictors and analysis is performed to understand the influence of these predictors on the final grades of the students.

# Methodology Employed
1. Exploratory Analysis
2. Fuzzy C-Mean 
3. Dimensionality Reduction (PCA)

# Fuzzy C-Mean 
The Fuzzy C-means (FCM) algorithm is a clustering technique used to group data points based on their similarities. It assigns each data point a membership value, indicating the degree to which it belongs to each cluster. The algorithm iteratively updates cluster centroids and membership values until convergence, aiming to minimize the intra-cluster variance. FCM allows data points to belong to multiple clusters simultaneously, providing a more flexible and nuanced clustering solution than traditional hard clustering methods.

# Dimensionality Reduction (PCA)
PCA stands for Principal Component Analysis. It is a statistical technique used to reduce the dimensionality of a dataset while preserving the most important information. PCA transforms the original variables into a new set of uncorrelated variables called principal components. These components are ordered by their ability to explain the variance in the data. By selecting a subset of principal components, one can represent the data in a lower-dimensional space while retaining the most significant patterns and structures. PCA is widely used in data analysis, visualization, and feature extraction tasks.
