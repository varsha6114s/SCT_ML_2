# SCT_ML_2
Customer Segmentation using K-means Clustering
This project uses K-means clustering to segment customers of a retail store based on their purchase history. By clustering customers based on features like annual income and spending score, we can gain insights into different customer groups and their purchasing behavior.

Table of Contents

Project Overview
Dataset
Project Structure
Requirements
Setup and Usage
Results
Project Overview The goal of this project is to segment customers of a retail store using K-means clustering, a popular unsupervised learning algorithm. By grouping customers based on purchasing behavior, retail businesses can tailor their marketing strategies to better suit the needs of different customer segments.

The project involves:

Data loading and preprocessing
Identifying the optimal number of clusters using the Elbow method
Performing K-means clustering
Visualizing the clusters in a 2D space using PCA
Dataset
The dataset contains information about customers, such as:

CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1-100) Note: The dataset is included in this repository as Mall_Customers.csv.
Project Structure

bash
Copy code
├── Mall_Customers.csv # Dataset file

├── README.md # Project documentation

└── kmeans_clustering.ipynb # Jupyter notebook with the clustering analysis

Requirements

Python 3.x
Jupyter Notebook
Libraries: pandas, numpy, matplotlib, seaborn, sklearn
You can install the required libraries with the following command:

* bash Copy code pip install pandas numpy matplotlib seaborn scikit-learn Setup and Usage Clone the Repository: Clone this repository to your local machine.

* bash Copy code git clone https://github.com/your-username/customer-segmentation.git

Upload Data to Google Colab (if using Colab): Run the Jupyter Notebook kmeans_clustering.ipynb in Google Colab or Jupyter Notebook.

Load and Preprocess the Data: Load the dataset and inspect it. Handle missing values if necessary and scale the features.

Determine Optimal Number of Clusters: Use the Elbow Method to determine the optimal number of clusters for the K-means algorithm.

Apply K-means Clustering: Set the optimal number of clusters and fit the K-means model to the data.

Visualize the Results: Use PCA to reduce the dimensionality of the data and plot the clusters.

Results After running the K-means clustering algorithm, the customers are segmented into distinct clusters, which can be visualized in a 2D plot. Each cluster represents a group of customers with similar purchasing behavior.
