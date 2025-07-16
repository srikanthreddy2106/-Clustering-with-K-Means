# -Clustering-with-K-Means

K-Means clustering, an unsupervised learning algorithm, was applied to the 'Mall Customers' dataset to segment customers based on their annual income and spending habits. This technique aims to partition data into 'K' distinct clusters, where each data point belongs to the cluster with the nearest mean.

The analysis began by selecting 'Annual Income (k$)' and 'Spending Score (1-100)' as features, which were then scaled to ensure equal contribution during clustering. The optimal number of clusters, 'K', was determined using the Elbow Method. By plotting the Within-Cluster Sum of Squares (WCSS) against various 'K' values, an "elbow" was clearly identified at K=5, indicating five as the most suitable number of customer segments.

Subsequently, K-Means was fitted with K=5, and cluster labels were assigned to each customer. The clusters were then visualized in a scatter plot, depicting distinct groups of customers with varying income and spending patterns, from high-income/high-spending to low-income/low-spending, and various combinations in between. The quality of this segmentation was quantified using the Silhouette Score, which yielded 0.4642, suggesting reasonably well-defined and separated clusters. These insights are invaluable for targeted marketing and strategic business decisions.

Sources
