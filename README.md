# CryptoClustering
## Module 19 Challenge
### By Eduardo Almonte

## 1. Find the Best Value for k Using the Scaled DataFrame
Code the elbow method to find the best k from a range of 1 to 11.

Plot a line chart of inertia values for each k to visually identify the optimal value.

## 2. Cluster Cryptocurrencies with K-Means (Scaled DataFrame)
Initialize K-means with the best k.

Fit K-means and predict clusters for the scaled data.

Add a column with cluster labels to the DataFrame.

Use hvPlot to create a scatter plot of cryptocurrencies, coloring by cluster.

## 3. Optimize Clusters with Principal Component Analysis (PCA)
Create a PCA model with 3 components.

Reduce the data to three principal components and check the explained variance.

Create a DataFrame using PCA data and repeat the elbow method to find the best k for clustering.

## 4. Visualize and Compare Results
Use hvPlot to create composite plots comparing:

## Elbow curves from the original and PCA data.
![elbow_curves](https://github.com/almonte951/CryptoClustering/blob/main/Images/elbow%20curves.png)

## Cluster results from the original and PCA data.
![clustering_results](https://github.com/almonte951/CryptoClustering/blob/main/Images/clustering%20results.png)

## Conclusion
By using both the original scaled data and PCA-reduced data, you can compare how clustering performance changes when using fewer features. This process helps optimize k-means clustering and provides insights into the importance of feature reduction when analyzing complex data like cryptocurrencies.

## Notes
This analysis was completed by building on insights from previous class activities on machine learning, with the support of ChatGPT for quick answers and efficient code generation.
