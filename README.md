# CryptoClustering
Python and unsupervised learning

In this challenge, we predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

•	The crypto_market_data.csv data is loaded into a DataFrame.

•	Summary statistics are obtained, and data is plotted.

•	The StandardScaler() module is used to normalize the data from the CSV file.

•	A DataFrame is created with the scaled data and the "coin_id" is set as an index from the original DataFrame into the new DataFrame.

•	The elbow method is used to find the best value for k

•	The cryptocurrencies are clustered for the best value for k on the original scaled data.

•	The original scaled DataFrame is used to perform a PCA and reduce the features to three principal components.

•	The explained variance is retrieved to determine how much information can be attributed to each principal component.

•	The elbow method is used on the PCA data to find the best value for k

•	The cryptocurrencies are clustered for the best value for k on the PCA data.

•	Composite plot is created by using hvPlot and the plus sign (+) operator to compare the elbow curve that is created from the original data with the one that is created from the PCA data

•	Composite plot is created by using hvPlot and the plus (+) operator to compare the cryptocurrency clusters that resulted from using the original data with those that resulted from the PCA data.


