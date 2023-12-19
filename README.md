# Cryptocurrency-Cluster-Analysis-with-Unsupervised-Machine-Learning

This is an assignment that focused on analysis using Unsupervised Machine learning using K Means, PCA, and StandardScaler.

# Background
I analyzed 42 cryptocurrencies in order to determine the effect of price changes over different periods of time.

# Organization
Repository has a readme file and a file labeled 'Code'. The Jupyter Notebook is named 'Crypto_Clustering_Working.ipynb' with my working code, plus a folder named 'Resources' which contains a single csv data file named 'crypto_market_data.csv'.

# Overview
- Scaled all of the data in the imported dataframe
- Determined the ideal K value for K Means using the elbow method
- Clustered all of the values using K Means with k value determined previously
- Optimized clusters with Principal Component Analysis (PCA)
- Calculated new optimal value of K
- Clustered the cryptocurrencies with K Means using the PCA data

# Discussion
four clusters was the optimal configuration. However, cluster distribution was much more apparent with the PCA method. This model showed a more distinct change in the slope of the elbow curve.
