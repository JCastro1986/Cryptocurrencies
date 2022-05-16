# Cryptocurrencies
# Module 18 Challenge - Unsupervised Machine Learning and Cryptocurrencies
- I need to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
- Since the data is not ideal I will need to be processed to fit the machine learning models.
- Since there is no known output for what I am looking for, I will be using unsupervised learning. 
- To group the cryptocurrencies I will be using clustering algorithm.
- Finlly I will be using data visualizations to share my findings with the board.

## Overview of the analysis: 
- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results

## Results: 

# Preprocessing the Data for PCA

- The first step was to performe data cleaning and the preparation process.
- The dataframe looked like the following:

* Image #1
![Image# 1](https://user-images.githubusercontent.com/95668609/168508121-f76fe8d4-c2b4-4155-a614-28aa6a4e0ddc.jpg)

# Reducing Data Dimensions Using PCA

- To be able to reduce the data dimension I needed to apply the PCA algorithm to reduce the dimensions to three principal components. 
- The new dataframe looks like the following:

* Image #2
![Image# 2](https://user-images.githubusercontent.com/95668609/168508127-10fb185f-d943-4e9e-bf22-875ff07f60b1.jpg)

# Clustering Cryptocurrencies Using K-means

- I later created an elbow chart to figure out the best option for the "K".
- The Elbow Curve is shown in the following image:

* Image #3
![Image# 3](https://user-images.githubusercontent.com/95668609/168508136-88597536-9560-4b1a-b32c-7af19bb76802.jpg)

- The K-means algorithm indicates the usage of 4 clusters to better predict the clusters for the data. 
- A new dataframe "clustered_df" was created and is shown in the following image:

* Image #4
![Image# 4](https://user-images.githubusercontent.com/95668609/168508142-e9632039-f49a-4694-b6be-009c5ee8781d.jpg)

# Visualizing Cryptocurrencies Results

- We can confirm the effectivness of 4 groups. 
- This was an acceptable number given the distribution of the data.

* Image #5
![Image# 5](https://user-images.githubusercontent.com/95668609/168508146-9eb159a9-0014-4ef3-9f9c-4c4f2e021c00.jpg)

- I then created a table with the hvplot.table functionality that is shown in the following image:

* Image #6
![Image# 6](https://user-images.githubusercontent.com/95668609/168508156-1fec21d5-c845-4600-aaf5-093eb29d8976.jpg)

- At the end it was possible to visualize the relationship between Total Coin Supply and Total Coins Mined by scaling those variables and plotting them on a scatter chart.

* Image #7
![Image# 7](https://user-images.githubusercontent.com/95668609/168508161-ef62eda4-ff05-4466-bb29-9251296d5e0e.jpg)
