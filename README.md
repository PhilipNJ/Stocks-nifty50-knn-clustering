# Clustering for Stock Data

We perform a K-means clustering for nifty50 stocks with an aim to diversify a portfolio with these bluechip stocks

Please note: This is not meant to be investment advice. Only for educational purposes

K-Means Clustering performed on Nifty50 stocks on the basis of price action from past 10 years

The following steps were followed:

1.     Using YFinance python package the information for the nifty50 tickers were extracted.

2.     New DataFrame created with daily close price, Annual returns and annual variance

3.     Inertia is calculated and based on elbow method number of clusters are calculated as 4 

<img width="408" alt="image" src="https://user-images.githubusercontent.com/97375173/162493503-369f568f-6c30-4abb-8398-df4e1d1bc706.png">

4.     We then fit the KMeans algorithm and get the cluster labels

<img width="388" alt="image" src="https://user-images.githubusercontent.com/97375173/162493613-96c02215-1b86-4d70-8c19-8f2bfda8eb17.png">

5.     A function is built to extract the stock with most returns in each cluster

<img width="481" alt="image" src="https://user-images.githubusercontent.com/97375173/162493723-b1653a1f-2b00-4fe6-a3f1-eeaa836ee33c.png">


