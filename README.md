# Cryptocurrencies


**Used clustering algorithm to group Cryptocurrencies**

Since there is no known output - used unsupervised learning.

## Steps

**Preprocessing the Data for PCA**

- Use pandas to preprocess data

- Remove unnecessary data (crypto that isnt being traded)

- Drop unneccesary columns


**Reducing Data Dimensions Using PCA**

- Reduced the dimension of the x dataframe to three principal components and placed these dimensions in a new dataframe.


**Clustering Cryptocurrencies Using K-means**

- Created an elbow curve using hvPlot to find the best value for 
K from the pcs_df DataFrame. 

- Ran K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

**Visualized Cryptocurrencies Results**

- Created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.


![3D-Scatter](https://user-images.githubusercontent.com/99001393/181049383-d017443d-73a9-4d95-9284-f35d74dce9b7.png)



![hvplot scatter](https://user-images.githubusercontent.com/99001393/181049420-9f022e1a-34bb-4358-8ac9-58e0ee32ddc4.png)
