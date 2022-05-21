# Unsupervised Machine Learning Challenge

## Cryptocurrency Clusters
### Data Preparation
* Read CSV File
* Discard all cryptocurrencies that are not being traded.
* Remove all rows that have at least one null value.
* Filter for cryptocurrencies that have been mined.
* Delete the CoinName from the original dataframe (dataset should be comprehensible to a machine learning algorithm)
* Convert "Algorithm" and "ProofType" into numerical data.
* Standardize the dataset so that columns that contain larger values do not unduly influence the outcome.  

### Dimensionality Reduction
* Perform dimensionality reduction with PCA with explained variation accounted for at 90%.
* Further reduce the dataset dimensions with t-SNE.
* Create a scatter plot of the t-SNE output.  
* Determine if there are clusters or not.  

### Cluster Analysis with k-Means
* Create an elbow plot to identify the best number of clusters.
* Determinek, if possible, where the elbow of the plot is, and at which value of k it appears.  

### Recommendation
Provide a recommendation to your clients: can the cryptocurrencies be clustered together?  If so, how many clusters.
