# Customer Behavior Analysis for Targeted Marketing Using K-Means

This repository contains a comprehensive analysis of customer behavior using the K-Means clustering algorithm to facilitate targeted marketing strategies.

## Project Overview
The goal of this project is to segment customers based on their spending behaviors and demographic information. By applying K-Means clustering, we identify distinct customer groups, enabling businesses to tailor marketing strategies more effectively.

## Project Preview
![Customer Data Visualization](Results/displot.png)
![Customer Data Visualization](Results/countplot.png)
![Customer Data Visualization](Results/scatterplot.png)
![Customer Data Visualization](Results/swarmplot.png)
![Customer Data Visualization](Results/customer_segmentation.png)
![Customer Data Visualization](Results/cluster_scatter_plot.png)
![Customer Data Visualization](Results/lineplot.png)
![Customer Data Visualization](Results/3d_plot.png)

## Project Stages
The analysis is structured into the following stages:

### 1. Importing Libraries
Essential Python libraries for data analysis and visualization are imported:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn (KMeans)

### 2. Data Exploration
Examination of dataset characteristics, including statistical summaries and initial observations of customer demographics and spending habits.

### 3. Data Visualization
Visual exploration of data distributions and relationships between variables.

### 4. Clustering using K-Means
Application of the K-Means algorithm to segment customers into meaningful clusters based on their spending scores and annual income.

### 5. 3D Plot of Clusters
Interactive visualization providing a clear representation of identified customer segments.

## Dataset Description
The dataset consists of 200 customer records with the following attributes:

| Attribute            | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| CustomerID           | Unique identifier for each customer                                          |
| Gender               | Gender of the customer (Male/Female)                                         |
| Age                  | Age of the customer                                                          |
| Annual Income (k$)   | Annual income in thousands                                                   |
| Spending Score (1-100) | Score assigned based on spending behavior (1 = low spender, 100 = high spender) |

## Key Findings
- Customers are grouped into distinct segments that highlight varying spending behaviors.
- Insights from clusters can significantly enhance targeted marketing efforts by identifying high-value customers and potential areas for growth.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn (KMeans)

## Future enhancements
- **Model Improvement:** Compare K-Means with DBSCAN, Agglomerative Clustering, and GMM. Automate optimal K selection using silhouette score or elbow method.

- **More Features:** Add demographics (e.g., location, marital status) and behavioral data (e.g., online activity, preferences).

## Contact

For questions or collaboration, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/vedantshinde25).
