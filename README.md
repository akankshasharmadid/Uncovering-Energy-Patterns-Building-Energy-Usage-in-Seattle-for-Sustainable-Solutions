**Uncovering Energy Patterns: Building Energy Usage in Seattle for Sustainable Solutions**

**Abstract:**

The issue of building energy consumption and its environmental impact in Seattle is a pressing concern. This research, based on Seattle’s Building Energy Benchmarking Program, aims to address the problem by developing a sophisticated model that can accurately analyze and forecast energy consumption patterns in various city buildings in Seattle. The study utilized the combination of supervised and unsupervised learning methods such as linear regression, clustering, and dimensionality reduction to discover underlying trends, patterns, and insights hidden in the large data set. By gaining a deep understanding of the dynamics of energy use, the research actively aims to promote sustainable practices, improve informed decision-making, and effectively reduce the environmental impact of building energy use in Seattle in real-time.

**Introduction:**

In the modern world, energy use in buildings and its impact on the environment are significant concerns. The objective of this study is to address the issue by utilizing the data from Seattle’s building Energy benchmark program which collects data every year. In this case study, we will utilize the 2021 Building Energy Benchmarking data by considering various factors such as demographic information, floor size, parking area and year built of the buildings in Seattle. The goal is to develop a model that can accurately assess and forecast trends of energy usage in buildings, considering the necessity for timely and effective solutions. By gaining a deeper understanding of energy consumption, we aim to contribute to the development of sustainable practices, inform decision-making processes, and mitigate the environmental impact caused by building energy consumption in Seattle.

**Theoretical Background:**

It's important to note that the PCA assumes linearity in the dataset and may not be suitable for non-linear relationships. PCA can be used to visualize the data in lower dimensions and fill in missing information in the dataset.

SVD stands for Singular Value Decomposition, which is a mathematical technique used for matrix factorization. It decomposes a matrix into three separate matrices, allowing valuable information about the matrix's structure and properties.

Given an m x n matrix A, the Singular Value Decomposition factorizes it into three matrices:

A = U Σ V^T

where:

- U is an m x m orthogonal matrix, whose columns are called the left singular vectors of A.
- Σ is an m x n diagonal matrix, with diagonal entries known as the singular values of A. The diagonal elements are arranged in descending order.
- V^T is the transpose of an n x n orthogonal matrix V, whose columns are called the right singular vectors of A.

PCA is equivalent to SVD when the data is pre-scaled in the SVD decomposition. Hence, SVD can be used to reduce the dimensionality of a dataset by selecting the top k singular values and their corresponding singular vectors. This technique is especially useful for large datasets and can help with noise reduction and extracting the most informative features. SVD can reveal the most common directions or qualities the data have.

An unsupervised learning technique called clustering is used to put comparable data points together based on their inherent properties. Clustering algorithms look at the data to find clusters or groupings of data points that share characteristics. The k-means algorithm is one clustering algorithm that is frequently utilized. In the k-means algorithm, the number of clusters to divide the dataset into needs to be specified. The algorithm starts by randomly assigning each data point to a intital cluster. It then iterates over each cluster, computing the centroid of each cluster, and reassigns the data points to the cluster based on the closest Euclidean distance to the centroid.

The k-means algorithm is sensitive to initialization, as it can find local minimum instead of the global minimum. To mitigate this issue, the algorithm can be run multiple times, and the version that yields the minimum cluster distance can be selected. The choice of the number of clusters is subjective and depends on the user's requirements and how the data is grouped within each cluster.

It is significant to note that PCA (Principal Component Analysis) and k-means both perform well with numerical data. The distance between data points and centroids is often measured using the Euclidean distance, and the data must be presented in a numerical manner. The within-group sum of squares is also influenced by the number of clusters selected, with more clusters leading to a smaller within-group total of squares. However, utilizing k-means to investigate various cluster alternatives can be computationally expensive, particularly for large datasets. Hierarchical clustering might be thought of as an alternate strategy in these situations. An unsupervised learning process called hierarchical clustering divides related data points into clusters according to how similar or dissimilar they are. Either top-down (divisive) or bottom-up (agglomerative), it builds a hierarchy of clusters. One advantage of hierarchical clustering is that it does not require a predefined number of clusters and it can be less time-consuming. It operates based on similar principles as the k-means algorithm.



**References:**

2021 Building Energy Benchmarking dataset. Retrieved from the Seattle Open Data portal [ https://data.seattle.gov/Community/2021-Building-Energy-Benchmarking/bfsh-nrm6 ]

**Authors**
- [@Akanksha Sharma](https://github.com/akankshasharmadid)
    [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akanksha-12831bb1)
    [![Leetcode](https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=LeetCode&logoColor=#d16c06)](https://www.leetcode.com/akanksha185/)
    

- [@Gokula Chandra ](https://github.com/gokula991)
  
