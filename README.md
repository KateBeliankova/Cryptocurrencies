## Cryptocurrency analysis

The present project was conducted to group all tradable cryptocurrencies into clusters. After preprocessing of the raw data (taken from https://min-api.cryptocompare.com/data/all/coinlist) , reduction dimensions with PCA to three, and drawing the elbow curve, it was determined that optimal number of clusters is four.
Once obtained clusters were visualized with 3D scatter plot it was concluded that we have 3 clusters and one currency that was defined as separate cluster(BitTorrent), so this currency might be treated as outlier.

For further analysis it might be helpful to exclude BitTorrent currency from the dataset and conduct analysis once again. To validate number of clusters it’s recommended to conduct Hierarchical clustering and draw a dendrogram.
