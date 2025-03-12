# Customer Behavior Analysis for Targeted Marketing Using K-Means

This repository contains a comprehensive analysis of customer behavior using the K-Means clustering algorithm to facilitate targeted marketing strategies.

## 📌 Project Overview
The goal of this project is to segment customers based on their spending behaviors and demographic information. By applying K-Means clustering, we identify distinct customer groups, enabling businesses to tailor marketing strategies more effectively.

## 🚀 Project Stages
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

## 🗃️ Dataset Description
The dataset consists of 200 customer records with the following attributes:

| Attribute            | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| CustomerID           | Unique identifier for each customer                                          |
| Gender               | Gender of the customer (Male/Female)                                         |
| Age                  | Age of the customer                                                          |
| Annual Income (k$)   | Annual income in thousands                                                   |
| Spending Score (1-100) | Score assigned based on spending behavior (1 = low spender, 100 = high spender) |

## 📊 Key Findings
- Customers are grouped into distinct segments that highlight varying spending behaviors.
- Insights from clusters can significantly enhance targeted marketing efforts by identifying high-value customers and potential areas for growth.

## ⚙️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn (KMeans)

## 📈 How to Run
To run this project locally:

1. Clone this repository:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```bash
    cd <project-directory>
    ```

3. Install required libraries:

    ```bash
    pip install numpy pandas matplotlib seaborn plotly scikit-learn
    ```

4. Run the Jupyter Notebook:

    ```bash
    jupyter notebook customer_analysis_kmeans.ipynb
    ```

## 🤝 Contribution
Contributions are welcome! Feel free to fork this repository, make improvements, and submit pull requests.
