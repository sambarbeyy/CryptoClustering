# CryptoClustering

Use the elbow method to find the best value for k using the following steps:

*Create a list with the number of k values from 1 to 11.

*Create an empty list to store the inertia values.

*Create a for loop to compute the inertia with each possible value of k.

*Create a dictionary with the data to plot the elbow curve.

*Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.

*Answer the following question in your notebook: What is the best value for k?

Use the following steps to cluster the cryptocurrencies for the best value for k on the original scaled data:

*Initialize the K-means model with the best value for k.

*Fit the K-means model using the original scaled DataFrame.

*Predict the clusters to group the cryptocurrencies using the original scaled DataFrame.

*Create a copy of the original data and add a new column with the predicted clusters.

Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.

Retrieve the explained variance to determine how much information can be attributed to each principal component and then answer the following question in your notebook:

*What is the total explained variance of the three principal components?

*Create a new DataFrame with the PCA data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.


<img width="807" alt="Screen Shot 2023-12-11 at 10 23 05 PM" src="https://github.com/sambarbeyy/CryptoClustering/assets/135924263/30178263-7313-4d57-92af-08fb2982e685">

<img width="939" alt="Screen Shot 2023-12-11 at 10 22 44 PM" src="https://github.com/sambarbeyy/CryptoClustering/assets/135924263/23c754ce-8ad7-4271-b4c3-9c7a8919cacf">

