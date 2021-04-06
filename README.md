# Cryptocurrencies

## Purpose
Using unsupervised learning, create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for new investment.   Since there is no known output, unsupervised learning using a clustering algorithm was considered the best approach.


### Resources
- Data Source: [cryto_data.csv](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/crypto_data.csv) 
- Software:
  - Python 3.6.1
- Libraries
  - Pandas
  - Path
  - plotly.express
  - sklearn
  - StandardScaler
  - MinMaxScaler
  - PCA
  - KMeans

### Preproccessing the Data
 - #### Keep All Cryptocurrencies Being Traded.
    -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/cryptocurrencies_being_traded.png) 
 - #### Keep All Cryptocurrencies that have Working Algorithms
    -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/crypto_with_working_algorithms.png) 
 - #### Find All Null Values
    -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/find_null_values.png) 
 - #### Use get_dummies() to Create Variables for Text Features.
    -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/get_dummies_for_text_features.png) 
 - #### Standardize the Data with StandardScaler.
    -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/standardScaler.png) 

### Reducing Data Dimensions
### Clustering Crytocurrencies using K-means.
### Visualizing Cryptocurrencies
