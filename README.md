# wine-clustering-pca
# Wine Clustering and PCA Analysis

## Overview
This project applies **Principal Component Analysis (PCA)** and **clustering algorithms** to the Wine dataset to uncover underlying patterns and structure in the data. The dataset consists of **178 wine samples**, each described by **13 chemical attributes** related to wine composition. The goal is to reduce dimensionality while maintaining interpretability and visualize distinct wine groups through clustering techniques.

## Features of the Project
- **Dimensionality Reduction**: Implementation of **PCA** to project data onto a lower-dimensional space while preserving variance.
- **Clustering Analysis**:
  - Application of **K-Means clustering** to classify wines into distinct groups.
  - Evaluation of clustering performance through visualization.
- **Cluster Optimization Analysis**:
  - The **Within-Cluster SSE** suggests that **3 clusters** is a reasonable choice, as the SSE curve flattens beyond this point.
  - The **Silhouette Score** peaks at **3 clusters**, indicating a good balance between compactness and separation.
- **Supervised Learning Baseline**:
  - Logistic Regression was used initially to establish a performance benchmark.
  - The model achieved **100% accuracy**, suggesting that the dataset has strong class separability.
  - This validates that clustering methods should be effective in grouping the wines correctly.
- **Visualization**: 3D plots using **Matplotlib** to illustrate principal components and clustering results.

## Dataset
The Wine dataset consists of the following attributes:
- **Chemical properties**: Alcohol, Malic Acid, Ash, Magnesium, Total Phenols, Flavanoids, etc.
- **Target variable**: Wine class label (1, 2, or 3).

## Insights & Results
- **PCA effectively reduced dimensionality** while retaining key characteristics.
- **Clustering results align well with the class labels**, showcasing clear separability among wine types.
- **Silhouette Score**: 0.2824, indicating moderate cluster separation.
- **Within-Cluster SSE**: 883.54, reflecting the compactness of clusters.
- **Cluster Optimization Findings**:
  - The **Within-Cluster SSE** suggests using **3 clusters**, as adding more clusters results in diminishing improvements in SSE.
  - The **Silhouette Score** also supports this choice, indicating a well-balanced clustering approach.
  
