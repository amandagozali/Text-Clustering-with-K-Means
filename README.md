# Text Clustering with K-means

This repository contains a notebook that demonstrates the use of the K-means algorithm, a popular unsupervised clustering algorithm, for clustering the national anthems of the world into different groups.

## Objective
The objective of K-means is to group similar data points together and discover underlying patterns within the dataset. The algorithm achieves this by searching for a fixed number (k) of centroids in the dataset. A centroid represents a cluster, which is a collection of data points that share certain similarities with each other. The 'means' in K-means refers to the averaging of the data, i.e., finding the centroid. Since the algorithm is unsupervised, it does not require prior knowledge about the groups or classes in the dataset. It autonomously identifies the underlying groups based on the data.

## Steps
1. Explore the collection of national anthems (corpus)
2. Perform data engineering on the dataset to optimize the performance of the K-means algorithm
3. Run the algorithm multiple times, testing with different numbers of clusters
4. Utilize various metrics to visualize the results and determine the optimal number of clusters (e.g., comparing the total number of clusters and their quality)
5. Conduct cluster analysis to gain insights from the clustering results

## Metrics for Determining the Best Number of Clusters
The following metrics will be used to evaluate and determine the best number of clusters:

- Elbow Method: This method helps identify the optimal number of clusters by evaluating the percentage of variance explained as a function of the number of clusters. The "elbow" point represents the number of clusters where adding more clusters does not significantly improve the model's performance.
- Silhouette Score: This metric measures how well each data point fits into its assigned cluster compared to other clusters. A higher silhouette score indicates that the data point is well-matched to its cluster and properly separated from neighboring clusters.

Feel free to explore the notebook for a detailed analysis of text clustering with the K-means algorithm using national anthems data.

## Dependencies
The following Python libraries are required to run the notebook:

- numpy
- pandas
- scikit-learn
- matplotlib

Install the dependencies using the following command:
pip install numpy pandas scikit-learn matplotlib


Enjoy clustering the national anthems with the K-means algorithm!

