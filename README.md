![download](https://user-images.githubusercontent.com/106290364/192929120-da2a47f8-0abf-4f16-97cb-80e617dfadb7.jpg)

# Crypto_Currencies


## Overview
This respitory is a analysis of multiple cryptocurrencies for an investment bank which is in the process of offering crypto as another avenue of investment for customers. Unsupervised machine learning was used for my analysis. The data was put in clusters and visualized. We used are returns from different periods and differenct crypto-currencies. These returns are standarized before starting the analysis.

## Clustering Cryptocurrencies Using K-Means
Using K-Means, we find different levels of inertia associted to different number of clusters (k), and plot results in a line plot. We then used the Elbow rule to decide which is the more appropiate and more efficient number of clusters in which to classify the data. k=4 is therefor the best choice, since after that the reduction in inertia.

## Clusters using standarized returns versus PCA
lusters are colored, and compared between original data and principal components for several terms. On the jupyter notebook plots, you can hover the name of the currencies. The final clusters are the same under both analysis, meaning standarized returns and PCA.

## Visualizing Results:
A 3D-Scatter plot was created using Plotly Express to plot the clusters. hvplot.table was used to create a data table with all the current tradable cryptocurrencies.
To present the clustered data about cryptocurrencies having x="TotalCoinsMined" and y="TotalCoinSupply" to contrast the number of available coins versus the total number of mined coins.

