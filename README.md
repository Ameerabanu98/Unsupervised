## Clustering : Unsupervised Machine Learning Algorithms
Clustering is an unsupervised learning technique in machine learning where the goal is to group a set of objects or data points into clusters or groups based on their similarity. Objects within the same cluster are more similar to each other than to those in other clusters. Clustering techniques are widely used in various fields, including data mining, pattern recognition, and machine learning, to discover hidden patterns or structures in data without prior labels.

#### Common clustering techniques include:

- KMeans Clustering
- Hierarchical Clustering

### KMeans Clustering
KMeans is a centroid-based clustering algorithm that partitions the data into K clusters, where K is a user-defined number. It assigns data points to the nearest cluster centroid and iteratively updates the centroids until convergence. KMeans is efficient and works well with large datasets when the number of clusters is known, but it assumes spherical clusters of similar size.

#### Key Features:
- Requires K (number of clusters) as input.
- Works best with spherical, equally-sized clusters.
- Sensitive to the initial placement of centroids.

### Hierarchical Clustering
Hierarchical Clustering creates a hierarchy of clusters, either by iteratively merging smaller clusters (agglomerative) or splitting larger clusters (divisive). The algorithm does not require specifying the number of clusters in advance. It produces a dendrogram, a tree-like diagram that visually shows the merging or splitting of clusters at each step. The number of clusters can be determined by cutting the dendrogram at the desired level.

#### Key Features:
- Does not require the number of clusters to be specified upfront.
- Provides a hierarchical tree (dendrogram) for data exploration.
- Computationally expensive for large datasets.
