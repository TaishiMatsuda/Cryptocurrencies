# Cryptocurrencies
Module 18 of UofT Data Analytics Boot Camp

#### Objective
The objectives of the module are to implement unsupervised machine learning techniques to categorize the cryptoCurrencies.

#### Resources
* Software / Services: Jupyter Lab
* Programming Language: Python
* Data: crypto_data.csv (from CryptoCompare)

#### Methods
1. Preprocessing (Cleanup, Converting Categorical Variable into Dummy Variables and Scaling)
2. Applying the PCA algorithm from sklearn
3. Creating an elbow curve to find the best K value
4. Applying the K-means algorithm to predict the K clusters for the cryptocurrencies

#### Results
The cryptocurrencies dataset was categorized into 4 clusters based on the shape of the elbow curve.
The brief explanation of the categories predicted by the K-means algorithm is as shown below;

* BitTorrent as its own category which uses unique Algorithm, TRC10, and has extremely large values supplied and mined.
* Category with Proof Type of PoS. 
* Category with Proof Type of PoW.
* Other with other Algorithm/Proof Types and small values supplied and mined.