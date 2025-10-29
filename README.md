Project 1 – Unsupervised Learning Alogrithm:Clustering-> K-Means & DBSCAN Clustering

OVERVIEW:
     This project focuses on Unsupervised Machine Learning, where data is grouped automatically without predefined labels. The goal is to identify hidden patterns and natural clusters in the dataset using K-Means and DBSCAN algorithms.
     Both algorithms are implemented, visualized, and their results are compared with real output plots and metrics.
OBJECTIVES:
  *Implement and understand clustering techniques.
  *Apply K-Means and DBSCAN algorithms.
  *Visualize and interpret cluster results.
  *Compare clustering performance with evaluation metrics.
  *Display meaningful output visualizations and results.
TECHNOLOGIES & LIBRARIES USED:
  *Python 3
  *NumPy – numerical computations
  *Pandas – data manipulation
  *Matplotlib & Seaborn – visualization
  *Scikit-learn (sklearn) – clustering algorithms & metrics
PROJECT WORKFLOwW:
  1)Data Preprocessing
        *Data loading and cleaning
        *Feature scaling using StandardScaler
  2)K-Means Clustering
         *Used Elbow Method to find the optimal number of clusters
         *Used Silhouette Score to validate cluster quality
         *Visualized cluster formation
  3)DBSCAN Clustering
          *Applied DBSCAN with tuned parameters (eps and min_samples)
          *Detected noise and non-linear clusters
           *Visualized the resulting clusters
COMPARISON:
      *Compared K-Means and DBSCAN visually and statistically
      *Observed differences in cluster shape and performance

RESULTS & OUTPUTS:
     ✔️ K-Means Output:
              *Clear circular clusters
              *Optimal number of clusters chosen using the Elbow method
              *Silhouette score indicates strong separation
     ✔️ DBSCAN Output:
              *Clusters formed based on density
              *Outliers and noise detected automatically
              *Works well with non-spherical clusters
VISUALIZATIONS INCLUDED:
      *Elbow Method Graph
      *Silhouette Score Plot
      *Scatter Plots for both algorithms
      *Cluster comparison visualization

Conclusion:
      *K-Means is best for structured, well-separated data.
      *DBSCAN handles irregular shapes and outliers better.
      *Both are useful for different types of datasets in unsupervised learning.
