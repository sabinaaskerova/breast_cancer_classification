# Breast Tumor Classification

## Overview
This project focuses on classifying breast tumors using a combination of gene expression data and medical variables. Key steps include data preprocessing, Principal Component Analysis (PCA), and K-Means clustering to identify distinct tumor classes.

## Results

### PCA and Variance Explained
- The PCA reveals that 70% of the information is captured by the first 26 components.

### Optimal Cluster Determination
- The optimal number of clusters (two clusters) is identified using the elbow method based on within-cluster sum of squares.

![scree](https://github.com/sabinaaskerova/breast_cancer_classification/assets/91430159/b95bc06e-4fb6-4b42-8d91-e704e51e4200)
*Elbow plot depicting the within-cluster sum of squares for different numbers of clusters.*

### Clustering Visualization
- The K-Means clustering results are visualized, showing clear separation between the two identified classes.
![pca_plot](https://github.com/sabinaaskerova/breast_cancer_classification/assets/91430159/f35295da-8169-4821-8b40-55b45aa8af7c)

### Association with Qualitative Medical Variables
- Chi-square tests identify integrative_cluster, pam50_._claudin.low_subtype, and X3.gene_classifier_subtype as the most significant qualitative medical variables associated with the tumor classes.

## Conclusion
The project classifies breast tumors into two distinct groups, revealing associations with specific gene expressions and qualitative medical variables. The identified variables provide valuable insights into the characteristics of these tumor classes.
