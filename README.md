# SCT_ML_2 - Customer Segmentation using K-means Clustering

This project uses K-means clustering to segment customers of a retail store based on their purchase history. By clustering customers based on features like annual income and spending score, we can gain insights into different customer groups and their purchasing behavior.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Setup and Usage](#setup-and-usage)
- [Results](#results)

## Project Overview

The goal of this project is to segment customers of a retail store using K-means clustering, a popular unsupervised learning algorithm. By grouping customers based on purchasing behavior, retail businesses can tailor their marketing strategies to better suit the needs of different customer segments.

The project involves:

1. Data loading and preprocessing
2. Identifying the optimal number of clusters using the Elbow method
3. Performing K-means clustering
4. Visualizing the clusters in a 2D space using PCA (Principal Component Analysis)

## Dataset

The dataset contains information about customers, such as:

- **CustomerID**: Unique identifier for each customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: The annual income of the customer (in thousands of dollars)
- **Spending Score (1-100)**: A score assigned to each customer based on their spending behavior (1-100 scale)

**Note:** The dataset is included in this repository as `Mall_Customers.csv`.
## Requirements

To run this project, you need:

- Python 3.x
- Jupyter Notebook

Additionally, the following libraries should be installed:

- pandas
- numpy
- matplotlib
- seaborn
- sklearn

## Setup and Usage

1. **Upload Data to Google Colab (if using Colab)**:
   - Upload the dataset and run the Jupyter notebook `kmeans_clustering.ipynb` in Google Colab or your local Jupyter Notebook environment.

2. **Load and Preprocess the Data**:
   - Load the dataset and inspect it. Handle any missing values if necessary and scale the features.

3. **Determine the Optimal Number of Clusters**:
   - Use the Elbow Method to determine the optimal number of clusters for the K-means algorithm.

4. **Apply K-means Clustering**:
   - Set the optimal number of clusters and fit the K-means model to the data.

5. **Visualize the Results**:
   - Use PCA to reduce the dimensionality of the data and plot the clusters in a 2D space.

## Results

After running the K-means clustering algorithm, the customers are segmented into distinct clusters. These clusters can be visualized in a 2D plot, where each cluster represents a group of customers with similar purchasing behavior.
