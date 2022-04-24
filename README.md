# Cryptocurrencies
## Module 18 - Unsupervised Machine Learning


In this challenge, I had to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for a new investment.

Unsupervised machine learning was used because there is no known output for this report. 

The cryptocurrency data was retrieved from CryptoCompare.

First the data was preprocessed to prepare it for PCA (Principal Component Analysis). This preparation included dropping columns that were not relevant and removing null values. The StandardScaler function was used to standardize the features in the DataFrame.

Next, the PCA was applied to reduce the dimensions of the DataFrame to three principal components. 

An elbow curve was created based on the K-means algorithm to find the best value for K. Then, the K-means algorithm was used to predict the K clusters for the dataset.

Finally, visualizations were created to show the distinct groups that correspond to the three principal components. The clusters were plotted on a 3D scatter chart with each data point showing the CoinName and Algorithm on hover. An easy-to-read table was created to show the tradeable cryptocurrencies. And a scatter plot represented the TotalCoinsMined and the TotalCoinSupply in a meaningful way. 