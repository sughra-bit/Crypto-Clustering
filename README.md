# Crypto-Clustering

Table of Contents
This assignment contains Resources folder which has crypto_market_data.csv file, 
Crypto_Clustering.ipynb, which is the script for the analysis

Challenge Objective
The objective of this challenge is to use knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Analysis

The dataframe data plotting

![Coin_id](https://github.com/sughra-bit/Crypto-Clustering/assets/135158002/d2752922-b8ed-46da-a973-458870c5bef0)


Elbow curve

![elbow curve](https://github.com/sughra-bit/Crypto-Clustering/assets/135158002/486abea5-fab2-41df-b50d-655a211660ad)

Cluster Cryptocurrencies with K-means Using the Original Data

![Price change](https://github.com/sughra-bit/Crypto-Clustering/assets/135158002/49749c82-7f7b-4501-9c77-f732fa838493)

Best Value for k Using the PCA Data
![elbow curve 2](https://github.com/sughra-bit/Crypto-Clustering/assets/135158002/da4cb91c-bb0d-4b73-aa38-821b59b69a1f)

Cluster Cryptocurrencies with K-means Using the PCA Data
![PCA1](https://github.com/sughra-bit/Crypto-Clustering/assets/135158002/948cf7d5-e332-4929-add4-29464598c442)

Visualize and Compare the Results
![EC1, EC2](https://github.com/sughra-bit/Crypto-Clustering/assets/135158002/4f53f9e2-8e58-4cc6-898d-f505fccd2885)



Questions & Answers
Question: What is the best value for k?

Answer: k = 4 is the best value
Question: What is the best value for k?

Question: What is the total explained variance of the three principal components?
Answer: 0.34871677, 0.31363391, 0.22627118

Question: What is the best value for k when using the PCA data?
Answer: The best k-value is k=4 when using PCA data

Question: Does it differ from the best k value found using the original data?
Answer: No, it is the same k value as found using the original data

Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?
Answer: The impact of using PCA data resulted in tighter clusters, it also resulted in more entries within cluster 0 and cluster 1 than the original analysis did.
