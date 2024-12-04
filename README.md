### Here I'll show how I work with unsupervised learning 
 
I'll solve next task here: 
  

Using [UNSW-NB15 Dataset](https://www.dropbox.com/s/nsvgwps3abdoxnq/clustering_data.zip?dl=1):
```
1. Preprocess the dataset 
    1. Dealing with categorical features 
    2. Data normalization
    3. Data standartization
2. Reduce dimension using PCA
3. Remove outliers
4. Cluster the data using K-means (find the optimal number of k with using two different types of scores to defind the best number of clusters:
4.1. Elbow method (sum of squared distances of samples to their centeroids VS number of clusters K) **Our goal in this method is to find a point from where decreasing  became not so crucial**
4.2. Silhouetta Score (It shows us how close each point in our cluster to points in neighboring clusters) **Here we have to take point with the hieghst result couse it will corrrespond that we are far from other clusters.** )

5. Visualize the data clusters (use PCA with 2 components)
```