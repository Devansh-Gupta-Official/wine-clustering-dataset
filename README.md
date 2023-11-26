# K-Means Clustering Analysis
This repository contains Python code for performing K-Means Clustering on a dataset and visualizing the clusters.

## **Dataset**
The analysis is conducted on the 'wine-clustering.csv' dataset.

# **Steps Involved**
1. Importing the Dataset: Load the dataset using pandas and prepare the data for clustering.
2. Determining Optimal Clusters: Utilize the Elbow Method to find the optimal number of clusters using within-cluster sum of squares (WCSS).
3. Training the K-Means Model: Implement K-Means Clustering with the optimal number of clusters.
4. Visualizing the Clusters: Plot the clusters and centroids using matplotlib to understand the groupings.
5. Silhouette Score: Calculate the silhouette score to evaluate the quality of clustering (optional step).

## **Usage**
1. Clone or download the repository.
2. Ensure the wine-clustering.csv file is available in your repository.
3. Open the Jupyter Notebook file in Jupyter Notebook or JupyterLab.
4. Run the cells sequentially to observe each step's output and analysis.
5. Customize the model by adjusting parameters, exploring different evaluation metrics, or using other datasets.

## **Files**
- k_means_clustering_Devansh Gupta.ipynb: Python script containing the entire process of K-Means Clustering.
- wine-clustering.csv: Dataset used for the analysis.

## **Results**
The K-Means Clustering algorithm with the optimal number of clusters showcased distinct groupings within the dataset. The average silhouette score achieved was 0.4247, indicating [brief interpretation of the score].
