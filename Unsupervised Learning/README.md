## Unsupervised Learning

## Definition
Unsupervised learning analyzes and clusters unlabeled data sets by machine learning algorithms. These algorithms find hidden patterns in data without the assistance of humans (thus the term "unsupervised"). The goal for unsupervised learning is to get some insights from a large dataset. One of the main objects for unsupervised learning is clustering. Clustering can group unlabeled data into groups based on similarities and differences. 

## Topic
#### K-Means Clustering

This algorithm is objected to partition the data space in such a way so that data points within the same cluster are as similar as possible (intra-class similarity), while data points from different clusters are as dissimilar as possible (inter-class similarity). In K-means, each cluster is represented by its center (called a “centroid”), which corresponds to the arithmetic mean of data points assigned to the cluster. A centroid is a data point that represents the center of the cluster (the mean), and it might not necessarily be a member of the dataset. This way, the algorithm works through an iterative process until each data point is closer to its own cluster’s centroid than to other clusters’ centroids, minimizing intra-cluster distance at each step.
