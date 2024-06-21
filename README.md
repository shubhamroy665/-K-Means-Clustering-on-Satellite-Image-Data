# -K-Means-Clustering-on-Satellite-Image-Data


## Overview

In this project, we implement the K-Means clustering algorithm from scratch to group data points from satellite images into clusters. K-Means clustering is a popular unsupervised learning algorithm that partitions data points into K clusters based on their features.

## Dataset

We utilized a satellite image dataset for clustering analysis. The dataset is included in the `data/` directory of this repository. You can substitute it with your own dataset following the provided structure.

## Implementation

Our implementation of the K-Means clustering algorithm can be found in the Jupyter Notebook `kmeans_band_image_tuhin_patra_version_no_1.ipynb`. Key components of our implementation include:
- **Initialization:** Random initialization of cluster centroids.
- **Assignment:** Assigning each data point to the nearest centroid based on Euclidean distance.
- **Update:** Updating centroids based on the mean of data points assigned to each cluster.
- **Visualization:** Visualizing the clusters formed by the algorithm.

## Repository Structure

- **data/:** Directory containing the dataset used for clustering analysis.
- **kmeans_band_image_tuhin_patra_version_no_1.ipynb:** Jupyter Notebook containing the code for implementing the K-Means clustering algorithm.

## Running the Notebook

To run the notebook:
1. Ensure Python and Jupyter Notebook are installed.
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/K-Means-Clustering-on-Satellite-Image-Data.git
   cd K-Means-Clustering-on-Satellite-Image-Data
