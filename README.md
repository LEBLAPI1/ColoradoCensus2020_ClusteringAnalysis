# Colorado 2020 Census Data Analysis and Unsupervised Learning

## Project Overview

This project involves an exploratory data analysis (EDA) and application of unsupervised machine learning techniques on the 2020 US Census dataset for the state of Colorado. The primary goal is to identify and analyze distinct demographic patterns within the state using clustering algorithms.

## Data Description

### Dataset Overview
The 2020 US Census dataset provides a comprehensive snapshot of the demographic, geographic, and social attributes of the US population. This analysis focuses specifically on the Colorado dataset, which includes variables such as:

- **Geographic Identifiers**: GEOID, GEOCODE, Census Tracts, etc.
- **Demographic Information**: Population counts by race and ethnicity.
- **Housing Data**: Housing unit counts and types of structures.
- **Urban and Rural Designations**: Urban areas and rural designations.

### Data Source
The dataset is publicly available and was sourced from the official US Census website. A summarized version of the dataset is also available on [Kaggle](https://www.kaggle.com/datasets/zusmani/us-census-2020).

## Methodology

### Exploratory Data Analysis (EDA)
The project begins with a thorough EDA to understand the key characteristics of the Colorado dataset, focusing on the distribution of demographic variables and identifying any notable trends or anomalies.

### Unsupervised Learning Techniques
The following unsupervised learning techniques are applied:

1. **K-Means Clustering**: Used to group similar demographic regions together.
2. **Principal Component Analysis (PCA)**: Applied to reduce the dimensionality of the dataset and visualize the clusters.
3. **t-Distributed Stochastic Neighbor Embedding (t-SNE)**: Further visualizes the clusters by representing high-dimensional data in a lower-dimensional space.

## Key Findings

- **Demographic Clusters**: The clustering analysis revealed several distinct demographic groups within Colorado. Some clusters showed strong concentrations of specific demographic groups, such as Latino populations, while others were more diverse.
- **Visual Insights**: PCA and t-SNE visualizations provided further insights into the structure of the data, showing both well-separated clusters and overlapping areas, which indicate similarities in demographic characteristics.

## Conclusion

The analysis successfully identified and visualized distinct demographic segments within Colorado, revealing valuable insights for various applications, including policymaking, community planning, and business strategy. Future work could explore additional clustering methods or consider more detailed socio-economic variables to refine the analysis further.
