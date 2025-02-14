# Clustering

## Overview
This project presents a comparative performance study of different clustering algorithms using various preprocessing techniques, different numbers of clusters, and multiple evaluation parameters.

## Methodology
1. **Dataset:** The Iris dataset from the UCI Machine Learning Repository is used.
2. **Preprocessing Methods:**
   - No Processing
   - Normalization
   - Log Transformation
   - PCA (Principal Component Analysis)
   - Transformation + Normalization
   - Transformation + Normalization + PCA
3. **Clustering Algorithms:**
   - K-Means
   - Hierarchical Clustering
   - Mean Shift
4. **Evaluation Metrics:**
   - Silhouette Score
   - Calinski-Harabasz Score
   - Davies-Bouldin Score

## Implementation
- A Colab notebook is created to perform the cluster analysis.
- The notebook is uploaded to GitHub for easy access.

## Results
Clustering experiments were conducted with different numbers of clusters (3, 4, and 5). Below is a summary of findings:

### Tables (Performance Metrics)
Each clustering algorithm's results are stored as CSV files.

### Graphs
- **PCA Clusters Visualization:** Scatter plots for K-Means clustering after PCA.
- **Evaluation Metrics:** Bar charts comparing different preprocessing techniques and cluster sizes.
- **Dendrograms:** Hierarchical clustering structure visualization.

## Key Findings
- **Normalization and PCA improved clustering performance**, leading to better separability in PCA plots.
- **K-Means performed well** with a reasonable number of clusters (3 or 4).
- **Hierarchical clustering showed meaningful structures**, as seen in dendrograms.
- **Mean Shift struggled with clear separations** due to dynamic cluster estimation.

## Conclusion
Applying PCA and normalization enhances clustering results. K-Means is a strong performer for structured data, while Hierarchical clustering provides useful hierarchical relationships. The project successfully evaluates clustering performance under different preprocessing conditions.

## Usage
Run the Colab notebook to generate clustering results and visualizations. The project is uploaded to GitHub for reference and reproducibility.