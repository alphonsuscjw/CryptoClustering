# CryptoClustering

This challenge uses K-means with Python to classify cryptocurrencies into different clusters based on their price changes in different intervals, using both the original data and the PCA.

This involved the steps below:
1) Data of the price changes in different intervals of various cryptocurrencies was read from a CSV file
2) Used the `StandardScaler()` module from scikit-learn to normalize the data
3) Found the best value for k using the original data with the elbow method
4) Created and used a K-means model using the best k value to cluster the cryptocurrencies using the original data
5) Created and used a PCA model with `fit_transform` to reduce the original data to 3 components
6) Found the best value for k using the PCA data with the elbow method
7) Created and used a K-means model using the best k value to cluster the cryptocurrencies using the PCA data
8) Visualised and compared the results
