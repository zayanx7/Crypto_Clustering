# Cryptocurrency Clustering Project

## Overview

This project focuses on clustering cryptocurrencies using the K-Means algorithm and Principal Component Analysis (PCA). The analysis involves normalizing the data, determining the optimal number of clusters (k) using the elbow method, and comparing clustering results between the original dataset and a reduced-dimensionality PCA dataset.

## Project Structure

The project is organized into the following sections:

1. **Data Preparation**
   - The data is loaded from a CSV file, and preprocessing steps include scaling using the StandardScaler module.

2. **Finding the Best Value for k Using the Original Data**
   - The elbow method is applied to identify the optimal number of clusters (k) for the K-Means algorithm using the original scaled data.

3. **Clustering Cryptocurrencies with K-means Using the Original Data**
   - The K-Means model is initialized and fitted using the best value for k obtained from the previous step.

4. **Optimizing Clusters with Principal Component Analysis**
   - PCA is performed on the original scaled data to reduce dimensionality to three principal components.

5. **Finding the Best Value for k Using the PCA Data**
   - The elbow method is employed again, but this time on the PCA data to identify the optimal k.

6. **Clustering Cryptocurrencies with K-means Using the PCA Data**
   - The K-Means model is initialized and fitted using the best value for k obtained from the PCA analysis.

7. **Visualize and Compare the Results**
   - Composite plots are created to contrast elbow curves and clustering results between the original and PCA data.

8. **Conclusion**
   - A conclusion is drawn based on the visual analysis of clustering results and the impact of using fewer features with PCA.

## Dependencies

- pandas
- hvplot
- scikit-learn