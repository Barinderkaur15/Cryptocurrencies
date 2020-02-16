# Cryptocurrencies
### Purpose : 
In this project, we used unsupervised learning to analyze data on Crytocurrencies traded on market 

### objective 

**1.** : Prepare the data for dimensions reduction with PCA and clustering using K-means..<BR>
**2** :  Reduce data dimensions using PCA algorithms from sklearn.<BR>
**3.** :Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.<BR>
**4.** :Create  plots and data tables to present your results.<BR>


### Various Models  and Alogorithms used 
**1.** sklearn.preprocessing.StandardScaler:Standardize features by removing the mean and scaling to unit variance.<BR>
**2.Principal component analysis(PCA)**<BR>
Linear dimensionality reduction using Singular Value Decomposition of the data to project it to a lower dimensional space. The input data is centered but not scaled for each feature before applying the SVD.

**3.K-Means clustering** <BR>
  K-means clustering is one of the simplest and popular unsupervised machine learning algorithms.Typically, unsupervised algorithms make inferences from datasets using only input vectors without referring to known, or labelled, outcomes.<BR>
To process the learning data, the K-means algorithm in data mining starts with a first group of randomly selected centroids, which are used as the beginning points for every cluster, and then performs iterative (repetitive) calculations to optimize the positions of the centroids.
  
  ###Challenge stpes 
**Step 1: Date Preprocessing** :Which is cleaning the data so that data can fit in model and make trhe right predictions .<BR>
1.Remove all cryptocurrencies that aren’t trading.
2.Remove all cryptocurrencies that don’t have an algorithm defined.
3.Remove the IsTrading column.
4.Remove all cryptocurrencies with at least one null value.
5.Remove all cryptocurrencies without coins mined.
6.Store the names of all cryptocurrencies on a DataFramed named coins_name, and use the crypto_df.index as the index for this new DataFrame.
7.Remove the CoinName column.
8.Create dummies variables for all of the text features, and store the resulting data on a DataFrame named X.
  
**Step 2 : Reducing Data Dimensions Using PCA**
Once we had reduced the data dimensions, we created a DataFrame named “pcs_df” that includes the following columns:

    PC 1
    PC 2
    PC 3
**Step 3 : Clustering Cryptocurrencies Using K-means**
**Step 4: Visualizing Results**
Created graph using plotly for 3D scatter plot and hvplot.scatter to create scatter plot and the used hvplot.tables to represent data in table form  
