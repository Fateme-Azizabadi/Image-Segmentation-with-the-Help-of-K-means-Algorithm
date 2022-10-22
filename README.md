# Image Segmentation with the Help of K-means Algorithm
**Image Segmentation with the Help of K-means Algorithm**

**In this project, we used the K-means algorithm to solve the image segmentation problem. In this problem, the goal is to separate the features of the image. We deal with a particular type of this problem: separation by image colors.**

## **Kmeans algorithm**

The Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the intra-cluster data points as similar as possible while keeping the clusters as different (far) as possible. It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid (arithmetic mean of all the data points that belong to that cluster) is at the minimum. The less variation we have within clusters, the more homogeneous (similar) the data points are within the same cluster.
This method aims to minimize the following function:
 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-K-means-Algorithm/blob/main/Images/Eq.png)

Where B(i) is the index of the category to which the ith data belongs

The way the K-means algorithm works is as follows:
Specify the number of clusters K.
Initialize centroids by shuffling the dataset and randomly selecting K data points for the centroids without replacement.
Keep iterating until there is no change to the centroids. i.e., the assignment of data points to clusters is not changing.
Compute the sum of the squared distance between data points and all centroids.
Assign each data point to the closest cluster (centroid).
Compute the centroids for the clusters by taking the average of all data points that belong to each cluster.

## **Implementation**
The K-Means algorithm is implemented from scratch in Python, and the explanations of each function and how they work are given in the Notebook of this question.

Each iteration checks whether the centers have moved or if their displacement is small, and the algorithm stops.

## **Result**

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-K-means-Algorithm/blob/main/Images/ponyo.jpeg)

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-K-means-Algorithm/blob/main/Images/k1.png)

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-K-means-Algorithm/blob/main/Images/k2.png)

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-K-means-Algorithm/blob/main/Images/k3.png)

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-K-means-Algorithm/blob/main/Images/k4.png)

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-K-means-Algorithm/blob/main/Images/k10.png)

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-K-means-Algorithm/blob/main/Images/k32.png)

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-K-means-Algorithm/blob/main/Images/k64.png)


 
