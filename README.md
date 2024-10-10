#Cryptocurrency Clustering and Analysis
##Overview
This project aims to analyze and cluster cryptocurrencies using K-Means clustering based on their price change percentages over 24 hours and 7 days. The analysis utilizes both original scaled data and data transformed through Principal Component Analysis (PCA) to determine optimal clustering and visualize the results effectively.

##Table of Contents
Features
Data
Requirements
Usage
Results
Contributing
License
Features
Optimal Clustering: Uses the elbow method to find the best value for k in K-Means clustering.
Visualizations: Generates elbow curves for both original scaled data and PCA-reduced data.
Comparative Analysis: Compares clustering results using both datasets to evaluate the impact of dimensionality reduction.
Interactive Visuals: Uses hvPlot for interactive scatter plots that represent cluster distributions and cryptocurrency identities.
Data
The dataset for this project is sourced from a CSV file containing cryptocurrency market data. It includes various features, with a focus on price change percentages over specified time intervals.

##Requirements
To run this project, you will need:

Python 3.x
Libraries:
pandas
numpy
matplotlib
scikit-learn
hvplot

Run the cells to perform the analysis and visualize the results.

Results
The project produces several key outputs, including:

Elbow curves for both original and PCA datasets to determine the optimal number of clusters.
Scatter plots visualizing the clustering results based on price change percentages.
Comparative plots to evaluate the differences in clustering results using original and PCA-transformed data.
