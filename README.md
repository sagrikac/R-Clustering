# R-Clustering


Link to the dataset https://archive.ics.uci.edu/ml/datasets/heart+Disease

Doctors frequently study former cases to learn how to best treat their patients. A patient who has a similar health history or symptoms to a previous patient could benefit from undergoing the same treatment. This project investigates whether doctors might be able to group together patients to target treatments using common unsupervised learning techniques

I have used the following two approaches:
K-Means and Hierarchical Clustering. 


K-means is an iterative algorithm that aims to partition data into K clusters so that each observation belongs to only one of the K clusters. The objective is to have a minimal “with-cluster-variation”, i.e., the elements in the same cluster should be as similar as possible. K-means achieves this goal by minimizing the distance of the points in a cluster with their centroid (arithmetic mean of all data within a cluster). In Euclidean geometry, we measure the pair-wise squared Euclidean distances. A point is considered to be in a particular cluster if it is closer to that cluster’s centroid than any other centroid.


The idea behind hierarchical clustering algorithms is quite different. Unlike the K-Means algorithm, the hierarchical algorithm does not require a representative for each cluster. Instead, It assumes that the clusters are hierarchically structured. That is, every cluster is made up of some smaller clusters. It treats the whole dataset as one big cluster and the sub-clusters contained in it are the partitions of the parent cluster. This assumption can be applied to its sub-clusters. The smallest unit will be a cluster that comprises only one singleton data point. The assumption of the algorithm allows us to interpret the resulting cluster structure as a tree, where the leaves of the tree represent the data points (clusters containing only one object) and the inner nodes represent the collection of all data points contained in its corresponding subtrees. Therefore, we can think of the process of hierarchical clustering algorithm as constructing a tree.
