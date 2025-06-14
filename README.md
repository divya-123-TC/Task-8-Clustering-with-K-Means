# Task-8-Clustering-with-K-Means
Task-8 Clustering with K-Means




 Customer Segmentation using K-Means Clustering

 Description:

This project demonstrates unsupervised learning using the K-Means Clustering algorithm to segment customers based on their Annual Income and Spending Score from the Mall Customers dataset.



 Objective:

Identify different customer segments based on purchasing behavior.

Determine the optimal number of clusters using the Elbow Method.

Evaluate cluster quality using the Silhouette Score.

Visualize the segmented groups using matplotlib and seaborn.



 Dataset Used:

Mall_Customers.csv

Features used:

Annual Income (k$)

Spending Score (1-100)




Libraries Used:

pandas

matplotlib

seaborn

sklearn.cluster.KMeans

sklearn.metrics.silhouette_score




 Workflow:

Step 1: Import Libraries

Basic libraries and tools were imported for data processing, clustering, and visualization.

Step 2: Load Dataset

Loaded dataset using pandas.read_csv() from local storage.

Step 3: Feature Selection

Selected two features for 2D visualization:

Annual Income (k$)

Spending Score (1-100)


Step 4: Elbow Method

Calculated inertia for different values of K (1 to 10) and plotted the Elbow Curve to identify the optimal number of clusters.

Step 5: Apply KMeans

Trained a KMeans model with K=5 and predicted customer segments.

Step 6: Visualization

Visualized the clusters in a 2D scatter plot using seaborn.

Step 7: Evaluation


 Output:

Silhouette Score: 0.55

A Silhouette Score closer to 1.0 indicates well-separated clusters.









---

Let me know if you want help creating a requirements.txt, Python script (.py), or a PDF summary of this.
