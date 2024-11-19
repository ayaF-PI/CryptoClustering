# CryptoClustering

# Overview

This project uses unsupervised machine learning techniques to analyze cryptocurrency data. The goal is to identify clusters of cryptocurrencies based on their price changes over different timeframes.

Technologies Used

	•	Python
	•	Jupyter Notebook
	•	Pandas
	•	Scikit-learn
	•	hvPlot

# Steps

1. Load and Prepare the Data

	•	Load cryptocurrency data from crypto_market_data.csv.
	•	Normalize the data using StandardScaler.

2. Elbow Method for Optimal k

	•	Use the Elbow Method on the scaled data to find the best number of clusters.
	•	Repeat the process on PCA-transformed data.

3. K-Means Clustering

	•	Apply K-Means clustering with the optimal k to both the original scaled data and PCA-transformed data.
	•	Visualize the clusters using hvPlot.

4. Principal Component Analysis (PCA)

	•	Reduce the dataset to three principal components.
	•	Analyze the explained variance.

5. Compare Results

	•	Compare the Elbow curves and clustering results for the original and PCA data.

# Results

	•	Found the optimal number of clusters (k).
	•	Visualized clusters for both original and PCA-transformed data.
	•	Compared clustering effectiveness using fewer features.

# Conclusion

Reducing features with PCA simplifies clustering while retaining most of the data’s variability.
