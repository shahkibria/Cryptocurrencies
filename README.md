# Cryptocurrencies

## Analysis Overview
In this project we used unsupervised machine larning to anlayze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified into clusters based on their features. This report could be used to categorize different currencies being traded in the market for further analysis. 

To accomplish our task, we processed the data to remove null values, filtered for onoly currencies which were traded and coins were mined. We then converted string variables into numeric variables using the "get_dummies" pandas function. After the data was processed, it was scaled using StandardScaler and data dimensions were reduced to three using PCA. 

Using the final PCA dataframe, we performed K-means clustering to categorize the data into 4 classes. We ended up at 4 clusters by utilizing the elbow curve. 