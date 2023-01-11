# Cryptocurrencies

## Overview of Project: 
One of the prominent investment bank is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. The task is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. Since there is no known output, I decided to use unsupervised machine learning  clustering algorithm to group the cryptocurrencies. 

### Steps:

1. Preprocessing the Data for PCA  ( Principal Component Analysis )

2. Reducing Data Dimensions Using PCA

3. Clustering Cryptocurrencies Using K-means

4. Visualizing Results 

## Analysis Results:

* Data Set

![Screenshot 2023-01-11 at 12 11 46 AM](https://user-images.githubusercontent.com/44387918/211756372-775b6f33-8618-4fa1-b84f-71431af94163.png)


* Remove the cryptocurrencies that are not in trading. 

![Screenshot 2023-01-11 at 12 24 19 AM](https://user-images.githubusercontent.com/44387918/211756320-2ce4fb83-32f8-45d3-b94f-65d7d0835cd5.png)


* Standardize the data  

![Screenshot 2023-01-11 at 12 32 35 AM](https://user-images.githubusercontent.com/44387918/211756753-085ca70c-d78a-43c1-b96c-2fe611ae60aa.png)


* Elbow curve to find the best value for K

![Screenshot 2023-01-11 at 12 13 27 AM](https://user-images.githubusercontent.com/44387918/211756204-b3e83738-9888-473c-a44c-a9cd3051806b.png)


* 3D-Scatter with Clusters

![Screenshot 2023-01-11 at 12 14 11 AM](https://user-images.githubusercontent.com/44387918/211756232-8dcbeb49-3eea-40a7-9dcc-53de91e0bab7.png)


* Scatter plot TotalCoinsMined vs TotalCoinSupply

![Screenshot 2023-01-11 at 12 14 47 AM](https://user-images.githubusercontent.com/44387918/211756261-80d369d9-ee1c-49d4-8ee8-307335b6e516.png)

### Summary: 
