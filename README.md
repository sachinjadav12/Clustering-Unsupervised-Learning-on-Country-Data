# Clustering-Unsupervised-Learning-on-Country-Data
Clustering the Countries by using Unsupervised Learning for HELP International Objective: To categorise the countries using socio-economic and health factors that determine the overall development of the country.

## Some Important Points to Emphasize:
Certain factors can affect the effectiveness of final clusters when using K-Means. Therefore, we must pay attention to the following details when solving problems using this algorithm:
#### Number of Clusters: 
The number of clusters in which you want to group your points directly influences the quality of the grouping. There are two main forms of evaluation to help choose k, the elbow method and the silhouette method.
#### Initial Values of the Centroids: 
The choice of the initial centers of the cluster can have an impact on the final formation of the cluster. As the initial selection of the k points for the centroid is random, if this choice is bad, it will generate bad clusters. However, there is a method to overcome this disadvantage of adjusting the initial values ​​called K-Means++. This method ensures smarter initialization of centroids and improves clustering quality.
#### Outliers: 
The formation of clusters is very sensitive to the presence of outliers. Outliers pull the cluster towards itself, affecting optimal cluster formation
#### Distance Measures: 
Using different distance measures (used to calculate the distance between a data point and the center of the cluster) can generate different clusters
#### Standardize the Data: 
As this is a measurement algorithm, your data must be numerical, not categorical, and it is always important to standardize them so that they are not in units of measurements that are very discrepant with each other, which can bias your results
#### Check Convergence: 
You should always check for convergence. The process may not converge in a given number of iterations

K-Means is one of the simplest and most popular clustering methods. Clustering is an unsupervised learning algorithm as it makes inferences from datasets using only input vectors without referring to known or labeled results.

Its goal is simple, to group similar data points and discover underlying patterns, but it is a computationally difficult (NP-hard) problem. However, there are efficient heuristic algorithms that are commonly employed and quickly converge to a local optimum, and one of them is K-Means.
To achieve this goal, K-Means looks for a fixed number (k) of clusters in a dataset. A cluster refers to a collection of data points grouped together due to certain similarities.
In the image below we visualize a data set on the left and the same set on the right after the creation of 3 clusters that best segments this data set.

### K-means is an unsupervised learning algorithm. K-Means has a function to group data into data clusters. This algorithm can accept data without any category labels. K-Means Clustering Algorithm is also a non-hierarchy method. The Clustering Algorithm method is grouping some data into groups which explains that data in one group has the same characteristics and has different characteristics from data in other groups.

