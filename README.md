# Customer Cluster Modeling using Unsupervised Machine Learning in Python

This project demonstrates customer segmentation using unsupervised machine learning techniques in Python. It utilizes the KMeans clustering algorithm to group customers based on their characteristics, behavior, and needs.

## Overview

Customer segmentation is a crucial task for businesses to understand their customer base and tailor their products and services accordingly. This project uses a dataset containing customer information, including demographics, purchase history, and other relevant features, to identify distinct customer segments.

## Libraries Used

-   **Pandas:** For data manipulation and analysis.
-   **NumPy:** For numerical computations.
-   **Matplotlib/Seaborn:** For data visualization.
-   **Scikit-learn (sklearn):** For data preprocessing, dimensionality reduction (TSNE), and clustering (KMeans).

## Dataset

The dataset used in this project is `new.csv`, which contains customer details such as marital status, income, purchase history, and other relevant information.

## Project Structure

-   `new.csv`: The dataset file.
-   `Customer_Segmentation.ipynb`: Jupyter Notebook containing the code and analysis.
-   `README.md`: This file.

## Setup and Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  **Install the required libraries:**

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3.  **Run the Jupyter Notebook:**

    ```bash
    jupyter notebook Customer_Segmentation.ipynb
    ```

## Data Preprocessing

The data preprocessing steps include:

-   Loading the dataset.
-   Handling missing values.
-   Converting categorical variables to numerical using Label Encoding.
-   Feature engineering (e.g., extracting day, month, and year from the date column).
-   Feature scaling using StandardScaler.
-   Removing unnecessary columns.

## Data Visualization and Analysis

-   Exploratory data analysis (EDA) using count plots, bar plots, and heatmaps.
-   Visualization of categorical and numerical features.
-   Correlation analysis.

## Segmentation using KMeans

-   Dimensionality reduction using t-SNE for visualization.
-   Determining the optimal number of clusters using the Elbow method.
-   Applying KMeans clustering to segment customers.
-   Visualizing the clusters using scatter plots.

## Usage

1.  Place the `new.csv` file in the same directory as the Jupyter Notebook.
2.  Open and run the `Customer_Segmentation.ipynb` notebook.
3.  Follow the steps in the notebook to perform customer segmentation.
4.  Analyze the resulting clusters to gain insights into customer behavior.

## Results

The project successfully identifies distinct customer segments based on their characteristics and behavior. The visualizations and analysis provide valuable insights for targeted marketing and product development.
