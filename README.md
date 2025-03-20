[1]  Customer Segmentation Using K-Means Clustering
 Project Overview
Understanding customer behavior is crucial for businesses to optimize marketing strategies.
This project applies K-Means Clustering to segment customers based on their purchasing patterns using the Online Retail dataset.
By identifying different customer groups, businesses can enhance customer retention, improve sales, and offer personalized services.

[2]    Dataset Overview
Dataset: Online Retail transactions dataset
Key Features:
Recency (R) – Days since last purchase
Frequency (F) – Number of transactions
Monetary Value (M) – Total revenue spent
Objective: Identify meaningful customer groups for targeted marketing strategies.


[3]    Data Preprocessing & Feature Engineering
Handled missing values and removed null entries.
Extracted RFM (Recency, Frequency, Monetary) features for customer segmentation.
Scaled data using StandardScaler for better clustering performance.
Determined the optimal number of clusters using the Elbow Method.


[4]    Model Development
Algorithm Used: K-Means Clustering (sklearn.cluster.KMeans)
Cluster Evaluation: Used Elbow Curve & Silhouette Score
Final Model: Trained on RFM features to segment customers into distinct groups.
Visualization: Applied PCA & Seaborn plots for better cluster representation.

[5]  Business Impact & Use Cases
✅ Targeted Marketing – Send personalized offers to different customer groups.
✅ Customer Retention – Identify high-value customers and improve engagement.
✅ Sales Optimization – Focus on the most profitable customer segments.


[5]   How to Use the Model
Load the trained model in python.



