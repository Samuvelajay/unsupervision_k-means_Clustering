# unsupervision_k-means_Clustering
This project performs customer segmentation on a mall customer dataset using unsupervised learning (K-Means clustering). The goal is to group customers into distinct segments based on their Annual Income, Spending Score, Age, and Gender, enabling targeted marketing and personalized strategies.
1. Data Preprocessing
Removed CustomerID
Label encoded Gender (Male → 1, Female → 0)
Standardized features using StandardScaler

2. Elbow Method for Optimal K
Plotted WCSS (Within-Cluster Sum of Squares) for k = 1 to 10
Found the optimal number of clusters using the Elbow Point

3. Model Training
Applied KMeans with k=3 to 7 clusters
Cluster labels were added to the dataset

4. Cluster Visualization
Visualized clusters using scatter plots based on:
Annual Income vs Spending Score
Cluster centroids marked in yellow

5. Cluster Characteristics
Inverse transformed standardized values to original scale
Analyzed the characteristics (mean values) of each cluster

6. Business Insights
Generated insights such as:
💸 Cluster 0: High income, low spending — might need targeted engagement
🤑 Cluster 1: High income, high spending — premium customers, focus on loyalty
🎯 Cluster 2: Moderate income/spending — potential to upsell with offers


