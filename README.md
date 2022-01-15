# Cryptocurrencies
# Unsupervised Machine Learning to identify the best crypto investments opportunities.

## Background
This is an exercise for a fictitious company Accountability Accounting, who is interested in offering a new cryptocurrency investment portfolio. It desired to make a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Approach:

* Importing the data using Pandas, perform data cleaning of nulls and zeros, text to numbers using get_dummies, and scaling of the data with the sklearn's StandardScaler function.

* The data was then reduced to 3 principle components using the PCA or Principle Component Analysis Algorithm from sklearn.

* Using the elbow curve method it was found that k=4 clusters was a good value.

![alt text](https://github.com/jj2773/cryptocurrencies/blob/main/elbowfig.PNG)

* The KMeans algorithm was leveraged to find the clustering or classes.

![alt text](https://github.com/jj2773/cryptocurrencies/blob/main/clusteringfig.PNG)

* Lastly the Clustering Class column was joined back to the original data set for tablular and plotting insights.  Note that the minmaxscaler function was used to scale the TotalCoinsMined and TotalCoinSupply for the below plot.

![alt text](https://github.com/jj2773/cryptocurrencies/blob/main/fulltable.PNG)

![alt text](https://github.com/jj2773/cryptocurrencies/blob/main/insightsfig.PNG)