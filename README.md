# PRODIGY_ML_02
Customer Segmentation using K-Means Clustering
This project demonstrates how to apply K-means clustering to segment customers based on their purchase history. The dataset used for this analysis is the Mall_Customers.csv file, which contains information about customers including their gender, age, and spending score. The goal is to group customers into clusters to identify distinct segments.

Files

Clustering_Customers(K_Mean).ipynb: Jupyter Notebook containing the K-means clustering implementation, data preprocessing, and analysis.
Mall_Customers.csv: CSV file with customer data used for clustering.

Project Description

1. Data Loading and Preprocessing
Load the customer data from Mall_Customers.csv.
Drop irrelevant columns (e.g., CustomerID).
Handle missing values by dropping rows with null values.
Standardize the data to ensure all features are on the same scale.
2. K-Means Clustering
Determine the optimal number of clusters using the Elbow method.
Fit the K-means algorithm with the chosen number of clusters.
Predict cluster labels for each customer and add them to the dataset.
3. Analysis
Analyze the characteristics of each cluster.
Calculate the Silhouette Score to evaluate the clustering quality.

Requirements
To run the Jupyter Notebook, ensure you have the following libraries installed:
pandas
scikit-learn
matplotlib

Results
The notebook provides visualizations and insights into customer clusters. The Elbow method is used to choose the optimal number of clusters, and the Silhouette Score is calculated to assess clustering performance.

Happy Coding!
