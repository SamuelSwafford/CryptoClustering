# CryptoClustering

## Overview
This project applies unsupervised learning techniques to cluster cryptocurrencies based on their market data. Utilizing Python libraries such as Pandas, scikit-learn, and hvPlot, we aim to identify patterns and group similar cryptocurrencies together. The analysis involves data preprocessing, dimensionality reduction using Principal Component Analysis (PCA), and clustering using the K-Means algorithm.

## Repository Structure
- Crypto_Clustering.ipynb
- README.md
- Resources/
- - crypto_market_data.csv

## Dependencies
To run the notebook, ensure you have the following Python libraries installed:
- Pandas
- hvPlot
- scikit-learn


## Running the Project

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Launch Jupyter Notebook and open `Crypto_Clustering.ipynb`.
4. Execute the cells in order to see the analysis from start to finish.

## Key Steps in the Analysis

1. **Data Preparation:** Load and normalize the market data of various cryptocurrencies.
2. **Finding the Best Value for k:** Utilize the elbow method to find the optimal number of clusters for K-Means clustering.
3. **Clustering with K-Means:** Apply K-Means clustering to the normalized data to identify cryptocurrency groups.
4. **Optimization with PCA:** Reduce dimensionality with PCA and repeat the clustering process to see its impact on the grouping.
5. **Visualization:** Visualize the clustering results to interpret and compare the effectiveness of the applied techniques.

## Conclusion

The notebook concludes with an analysis of the clustering results, including a comparison of clusters before and after dimensionality reduction with PCA. This project showcases the power of unsupervised learning in grouping data without predefined labels.
