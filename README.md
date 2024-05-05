# CryptoClustering
Module 19 Challenge - Crypto Clustering


![CryptoClustering-06](https://github.com/Adykey79/CryptoClustering/assets/149746353/50a3d101-1824-4acc-ba6c-7f1e975ad286)


### K-value algorithm
* Find the Best Value for K using the Original Scaled Data Frame The best K value is 4 after the calculation.
Apply the K-means algorithm to cluster Cryptocurrencies.

### PCA & K-value algorithm
* Perform a PCA to reduce the features to three principal components.
Calculate the total explained variance. The result is 0.8950316570309841.
Find the Best Value for k after PCA and the best K value is 4.
Apply the K-means algorithm to cluster Cryptocurrencies after PCA.

### Summary
* The best clusters are 4 and the PCA reduced the dimensionality of the dataset and combined all variables/features tighter to generate new PCA variables. These provide us with better visualization for clustering. “market_plot” using K-Means from scaled dataset has some overlap. However, after PCA, the dataset has been divided clearly into 4 clusters.
