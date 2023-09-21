# Crypto_clustering
Background:
In this challenge, I used Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
Use the StandardScaler() module from sci-kit-learn to normalize the data from the CSV file.
Initialize the K-means model with the best value for k.
Fit the K-means model using the original scaled data frame.
Predict the clusters to group the cryptocurrencies using the original scaled DataFrame.
Create a copy of the original data and add a new column with the predicted clusters.
Create a scatter plot using hvPlot as follows:
Set the x-axis as "PC1" and the y-axis as "PC2".
Color the graph points with the labels found using K-means.
Add the "coin_id" column in the hover_cols parameter to identify the cryptocurrency represented by each data point.


Optimize Clusters with Principal Component Analysis
Using the original scaled data frame, perform a PCA and reduce the features to three principal components.

Diagrams:
prepared elbow 1 and market 1 prediction, and elbow 2 and market 2 prediction, and both compared.
Result is  Both yield similar results. Data is grouped in clear segments in both.

<img width="920" alt="Screenshot 2023-09-21 113147" src="https://github.com/stargily2017/Crypto_clustering/assets/117419179/849c106c-cc24-4024-b128-95d4209ba100">


1.Blue represents cryptocurrencies with the worse performance of the set. Negative or small return in all periods (short, middle and long term). (For example, stellar, iota, okb) 2.Red performs a little better than the blue ones. Those are cryptos with moderate positive or slighly negative in the short term returns (ie. wrapped-bitcoin, litecoin, bitcoin-cash, maker) 3.Green performs really well in the long term, short terms returns (ie. Ethlend) 4.Yellow performs well in the long term side, not in the short term.(ie. celcius-degree-token)
