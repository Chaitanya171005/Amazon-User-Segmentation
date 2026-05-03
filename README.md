Overview

Understanding customer behavior is essential for e-commerce platforms like Amazon to improve customer satisfaction and business growth. This project focuses on segmenting Amazon users into different groups based on their Age, Annual Income, and Purchase Rating using machine learning clustering techniques.
The project applies Agglomerative Clustering to identify meaningful customer segments and analyze purchasing behavior patterns.

Objective

The primary objectives of this project are:

*Segment Amazon users into different customer groups
*Identify hidden behavioral patterns among users
*Analyze customer purchasing trends
*Improve targeted marketing strategies
*Support personalized recommendation systems

Dataset

Features used: Age, Income, Rating

Methodology

Data Preprocessing
 
The dataset was preprocessed before applying clustering algorithms.
Preprocessing Steps:
Handling missing values
Feature selection
Data normalization using StandardScaler

Model Used

Agglomerative Clustering
 
Agglomerative Clustering is a hierarchical clustering algorithm that follows a bottom-up approach:
Each customer initially represents an individual cluster
Closest clusters are merged iteratively
The process continues until meaningful customer groups are formed
This approach helps identify natural relationships among users based on their income, age, and ratings.

K-Means Clustering

K-Means Clustering is an unsupervised machine learning algorithm used to group similar data points into clusters.

The algorithm works as follows:

1. Select the number of clusters (K)
2. Initialize cluster centroids randomly
3. Assign each data point to the nearest centroid
4. Update centroid positions based on cluster averages
5. Repeat the process until clusters stabilize

The model groups Amazon users based on similarities in age, income, and purchase ratings.


Finding Optimal Number of Clusters

The Elbow Method was used to determine the optimal number of clusters for the K-Means model.

The method works by plotting:

* Number of clusters (K)
* WCSS (Within-Cluster Sum of Squares)

The optimal value of K is identified at the point where the graph forms an “elbow,” indicating minimal improvement after that point.

Visualization

The visualization represents the customer segmentation results obtained using the K-Means Clustering algorithm. Each point in the graph corresponds to an Amazon user, where:

X-axis: User Age
Y-axis: Product Rating given by the user

Different Colors: Different customer clusters identified by the algorithm

Users with similar age groups and rating patterns are grouped together.

Some clusters represent young users who provide high ratings, indicating satisfied and engaged customers.
Other clusters may represent users with average or low ratings, which can help identify areas for improving customer experience.

Businesses can use these insights for:

1.Personalized recommendations

2.Targeted marketing campaigns

3.Customer retention strategies

4.Product improvement analysis

The scatter plot provides an intuitive understanding of customer behavior and demonstrates the practical application of unsupervised machine learning in e-commerce analytics.


