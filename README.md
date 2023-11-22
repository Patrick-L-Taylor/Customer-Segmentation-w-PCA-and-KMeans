
# Customer Segmentation with PCA and KMeans




## Project Overview
This project demonstrates customer segmentation using Principal Component Analysis (PCA) and KMeans clustering. Using a dataset of wholesale customers, the project aims to uncover underlying customer segments based on their purchasing behavior across various product categories.

## Objectives
Perform dimensionality reduction on customer transaction data using PCA and Kernel PCA.
Apply KMeans clustering to segment customers.
Visualize and interpret the segmented customer groups.

## Methodology

### Data Preprocessing:

Data is loaded from 'Wholesale customers data.csv'.
Renaming columns for clarity, e.g., 'Delicassen' to 'Delicatessen'.
Mapping numerical categories to descriptive labels in 'Channel' and 'Region'.
Data exploration using value_counts() and describe().

### Exploratory Data Analysis:

Utilizing Matplotlib and Seaborn for data visualization.
Generating histograms and bar charts for each feature to understand distributions.
Creating pair plots to observe relationships between different features.

### Dimensionality Reduction:

Standardizing the data with StandardScaler.
Applying PCA to reduce dimensions to two principal components.
Exploring Kernel PCA with different kernels (RBF, Polynomial, Cosine) for further dimensionality reduction.

### Customer Segmentation with KMeans:

Implementing KMeans clustering on the reduced datasets.
Determining the optimal number of clusters using the Elbow method with KElbowVisualizer.
Visualizing the clusters in the reduced feature space.

### Cluster Analysis and Visualization:

Assigning cluster labels back to the original DataFrame.
Grouping data by cluster labels to find average values for each feature.
Utilizing Plotly for interactive visualization of the clusters in a radar plot format.
Saving the interactive plot as 'Demo.html' for easy sharing and presentation.

## Key Findings
Insights into customer behaviors and preferences based on clustering results.
Identification of distinct customer segments based on purchasing patterns.
Observations on the effectiveness of different kernels in Kernel PCA on segmentation quality.

## Technologies Used
Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Plotly, Jupyter Notebook.

## Running the Project
Detailed instructions on how to run and reproduce the analysis, including required packages and steps to execute the Jupyter notebook.













## Project Overview:

Brief introduction to customer segmentation and its importance in marketing and sales strategies.
Mention the use of Principal Component Analysis (PCA) and KMeans clustering in the project.
Highlight the use of Python for data processing and analysis.

## Objectives:

Outline the main objectives of the project, such as understanding customer behaviors, segmenting customers based on transaction data, and visualizing customer segments.

## Methodology:

Data Preprocessing: Description of initial data exploration and preprocessing steps.
Dimensionality Reduction: Explanation of how PCA and Kernel PCA were applied to the dataset.
Customer Segmentation: Discuss the application of KMeans clustering for segmenting customers.
Visualization and Evaluation: Mention the tools and techniques used for visualizing the clustered data and how the segmentation was evaluated.

## Results and Key Findings:

Summarize the key insights gained from the segmentation, such as distinct customer behaviors or characteristics of different segments.
If applicable, include any surprising findings or challenges encountered during the analysis.

## Technologies Used:

List the main technologies, libraries, and tools used in the project (e.g., Python, Pandas, Scikit-learn, Plotly Dash).
How to Run the Project:

Provide instructions on how to set up and run the project, including any required installations or dependencies.


GitHub Repository Contents:
Data Folder (/data): Contains the datasets used in the project.
Scripts Folder (/scripts): Python scripts for data preprocessing, PCA, and KMeans clustering.
Notebooks Folder (/notebooks): Jupyter notebooks demonstrating the step-by-step process of the analysis.
Visualizations Folder (/visualizations): Includes plots and graphs generated during the analysis.
Results Folder (/results): Contains the output files, such as segmented customer data.
README.md: The detailed project description as outlined above.
