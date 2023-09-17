# CryptoClustering
Unsupervised Machine Learning Using Python

In this challenge, I used Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. 

## Steps Involved:

1. The crypto_market_data.csv file was loaded into a data frame. A line graph was plotted for a better understanding of the data.

2.  The StandardScaler() module from sci-kit-learn was used to normalize the data from the CSV file.

3. A data frame was created using the scaled data, and the "coin_id" column from the original data frame was set as its index.

4. The elbow method was used to select the best value of k using the scaled dataset. A line chart was plotted with all the inertia values computed with different values of k to identify the optimal value of k visually.
<img width="551" alt="image" src="https://github.com/bhartikaushal/CryptoClustering/assets/124011061/bede2645-8d7d-49ef-af77-16e70e1fbc58">


5. Cryptocurrencies were clustered for the best value for k on the original scaled data. A scatter plot was created using hvPlot for visualization.

 <img width="539" alt="image" src="https://github.com/bhartikaushal/CryptoClustering/assets/124011061/c490aec1-d2ad-4e7c-bb03-1065fb098bee">


6. Principal Component Analysis was used to optimize clusters. PCA was performed on the original scaled dataset to reduce the features to three principal components. Explained variance was retrieved to determine how much information can be attributed to each principal component.

7. The elbow method was used on the PCA data to find the best value for k. A line chart was plotted with all the inertia values computed with the different values of k to visually identify the optimal value of k.

8. Cryptocurrencies were clustered with K - means using the PCA data. A scatter plot was created using hvPlot. Using PCA, we plotted a graph with two distinct clusters that are easy to understand and provide meaningful insight into the data.
   <img width="540" alt="image" src="https://github.com/bhartikaushal/CryptoClustering/assets/124011061/2700c055-76b0-4db6-b75c-397b33ad54b5">
   

   



