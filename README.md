# Clustering Assignment – UCI Dataset - Iris

**Name**: Trish Rustagi  
**Roll No.**: 102203584

## Project Overview

This project explores the performance of various clustering algorithms on a small dataset from the UCI Machine Learning Repository. We evaluate the clustering quality using different preprocessing techniques and compare metrics across:

- **K-Means Clustering**
- **Hierarchical Clustering**
- **K-Mean Shift Clustering**

### Objectives

- Perform clustering with multiple algorithms.
- Analyze the effect of different preprocessing methods:
  - No Processing
  - Normalization
  - Log Transformation
  - PCA
  - Combinations: Transform + Normalize, Transform + Normalize + PCA
- Evaluate clusters using:
  - **Silhouette Score**
  - **Calinski-Harabasz Index**
  - **Davies-Bouldin Index**

## Dataset

The dataset used is from the **UCI Machine Learning Repository** (here, the Iris dataset).

- Features: Numerical
- Target: Unused (unsupervised clustering)

## Preprocessing Techniques

- **Normalization**: Scales features between 0 and 1.
- **Log Transform**: Applies `log1p` to stabilize variance.
- **PCA**: Reduces dimensionality while retaining 95% variance.

## Evaluation Metrics

| Metric                | Description |
|-----------------------|-------------|
| Silhouette Score      | Measures how well clusters are separated |
| Calinski-Harabasz     | Higher is better, indicates cluster density |
| Davies-Bouldin Index  | Lower is better, measures intra/inter-cluster ratio |

## Results:

Below is a sample of how the results are structured for the Iris Dataset:
![image](https://github.com/user-attachments/assets/01a91d06-4a27-4838-8fa4-07ab228c5cb8)


