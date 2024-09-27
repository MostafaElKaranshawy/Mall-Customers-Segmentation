
# Mall Customer Segmentation

## Problem Description

This project aims to analyze customer data for segmentation using clustering techniques. The goal is to identify distinct customer groups based on their characteristics, such as income, spending score, and other demographic data. This type of analysis is useful for businesses to tailor marketing strategies, improve customer experience, and optimize resource allocation.

## Model

The project applies **K-Means clustering** to group customers into clusters. This unsupervised learning algorithm partitions the dataset into clusters based on similarities in features, minimizing intra-cluster variance and maximizing inter-cluster variance. The notebook explores and visualizes how different customer attributes contribute to these clusters.

### Key Steps

1. **Data Loading and Preprocessing**: The dataset is cleaned and features are normalized for better clustering performance.
2. **Model Training**: The K-Means algorithm is applied to find the optimal number of clusters.
3. **Visualization**: The results are visualized to show how different features (like income, spending score, etc.) impact the clustering.

## Libraries

The following libraries are used in this project:

- **pandas**: For data manipulation and preprocessing.
- **numpy**: For numerical operations and array manipulations.
- **matplotlib**: For visualizing the clusters and relationships between features.
- **sklearn**: For implementing the K-Means clustering algorithm.

## Usage

To use the notebook, follow these steps:

1. Clone the repository or download the notebook.
2. Ensure you have the required libraries installed:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Run the notebook cell by cell. You can modify parameters like the number of clusters to see how it impacts the clustering.

## Input Data

- The dataset used in this project includes various customer attributes such as gender, annual income, and spending score. Ensure the dataset is properly formatted and loaded before running the model.

<hr>

[See the Problem on Kaggle](https://www.kaggle.com/code/mustafaelkaranshawy/mall-customer-clustering)