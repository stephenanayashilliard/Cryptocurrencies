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
 - #### Reduce Dimensions to Three Principal Components
   -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/reduce_dimensions_to_three_components.png) 
 - #### Create DataFrame with Three Principal Components
   -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/reduce_dimensions_to_three_components.png) 

### Clustering Crytocurrencies using K-means.
 - #### Find the Best Value for k Using the Elbow Curve
   -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/Elbow_curve_for_k.png)
 - #### Initialize the K-Means Model with k=4.
   -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/initialize_Kmeans_Model.png) 

### Visualizing Cryptocurrencies
 - #### 3D-Scatter with Clusters
  -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/3D-Scatter.png)
 - #### Hvplot.scatter Plot 
  -![](https://github.com/stephenanayashilliard/Cryptocurrencies/blob/main/Resources/hvplot_scatter.png) 
  
# Contact Information
Email: Stephenanayashilliard@gmail.com

Linkedin: [Linkedin for Stephen Anayas-Hilliard](https://www.linkedin.com/in/stephen-anayas-hilliard-942a8431/)
