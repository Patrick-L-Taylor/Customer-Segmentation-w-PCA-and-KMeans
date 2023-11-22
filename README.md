
# Customer Segmentation with PCA and KMeans

## Project Overview
This project demonstrates customer segmentation using Principal Component Analysis (PCA) and KMeans clustering. Using a dataset of wholesale customers, the project aims to uncover underlying customer segments based on their purchasing behavior across various product categories.

## Objectives
Perform dimensionality reduction on customer transaction data using PCA and Kernel PCA.
Apply KMeans clustering to segment customers.
Visualize and interpret the segmented customer groups.

## Technologies Used
Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Plotly, Jupyter Notebook.

## Methodology

#### Data Preprocessing:

 - Data is loaded from 'Wholesale customers data.csv'.
 - Renaming columns for clarity.
 - Mapping numerical categories to descriptive labels in 'Channel' and 'Region'.
 - Data exploration using value_counts() and describe().

#### Exploratory Data Analysis:

 - Utilizing Matplotlib and Seaborn for data visualization.
 - Generating histograms and bar charts for each feature to understand distributions.
 - Creating pair plots to observe relationships between different features.

#### Dimensionality Reduction:

 - Standardizing the data with StandardScaler.
 - Applying PCA to reduce dimensions to two principal components.
 - Exploring Kernel PCA with different kernels (Radial Basis Function, Polynomial, Cosine) for further dimensionality reduction.

#### Customer Segmentation with KMeans:

 - Implementing KMeans clustering on the reduced datasets.
 - Determining the optimal number of clusters using the Elbow method with KElbowVisualizer.
 - Visualizing the clusters in the reduced feature space.

#### Cluster Analysis and Visualization:

 - Assigning cluster labels back to the original DataFrame.
 - Grouping data by cluster labels to find average values for each feature.
 - Utilizing Plotly for interactive visualization of the clusters in a radar plot format.
 - Saving the interactive plot as 'Demo.html' for easy sharing and presentation.

## Key Findings
Insights into customer behaviors and preferences based on clustering results.
Identification of distinct customer segments based on purchasing patterns.
Observations on the effectiveness of different kernels in Kernel PCA on segmentation quality.


## Github Repository Contents
 - Jupyter Notebook (Customer-Segmentation-w-PCA-and-KMeans.ipynb): Jupyter Notebook for completing the Analysis
 - Data Folder (/Data): Contains the datasets used in the project.
 - HTML Visual (Demo.html): Cluster Analysis HTML created with Plotly

