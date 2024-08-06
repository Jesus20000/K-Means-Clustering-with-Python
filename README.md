# K Means Clustering with Python

## Overview
This project demonstrates the use of the K Means Clustering algorithm, an unsupervised learning method, to cluster data points into groups based on their similarity. K Means Clustering does not require labeled outcomes and aims to find patterns and group similar data points together.

## Libraries Used
- `seaborn` (for data visualization)
- `matplotlib` (for plotting)
- `sklearn` (for K Means Clustering and generating sample data)

## Data
In this project, synthetic data is generated using the `make_blobs` function from the `sklearn.datasets` module. The dataset consists of 200 samples with 2 features, grouped into 4 clusters. The data is visualized before and after clustering to demonstrate the effectiveness of the K Means algorithm.

## Analysis Steps
1. **Import Libraries**: Required libraries are imported for data visualization and clustering.
2. **Create Data**: Generate synthetic data with `make_blobs` to simulate a clustering scenario.
3. **Visualize Data**: Plot the generated data to observe its distribution.
4. **Create Clusters**: Apply the K Means Clustering algorithm to the data.
5. **Visualize Clusters**: Plot the clustered data and compare it to the original data to assess clustering performance.

## Insights
- The K Means algorithm effectively groups the data into the specified number of clusters.
- Visualization of clusters helps in understanding how well the algorithm has performed and how the data points are distributed among clusters.

## Conclusion
The K Means Clustering algorithm is a powerful tool for unsupervised learning and pattern recognition. By specifying the number of clusters, we can identify distinct groups within the data. This project demonstrates the basic functionality of K Means and its application to synthetic data.

## Requirements
To run this project, you need to install the following Python libraries:
- `seaborn`
- `matplotlib`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install seaborn matplotlib scikit-learn
