# TaskCode_task2
# Prodigy_TaskCode_task2
🛍️ Customer Segmentation using K-Means Clustering
This project is part of Task 2 from the Prodigy Internship Program. It applies unsupervised machine learning to segment customers based on their annual income and spending score, helping businesses understand customer behavior for targeted marketing.

📁 Dataset
The dataset includes information about customers such as:

Annual Income (k$): Yearly income in thousands of dollars.
Spending Score (1–100): Score assigned based on customer spending behavior.

🔹 Note: The dataset filename should be added in the read_csv() function before running.

🎯 Objective
Perform K-Means Clustering on the customer data to group them into segments.
Visualize the optimal number of clusters using the Elbow Method.
Plot the final customer segments for easy interpretation.

🔧 Technologies & Libraries Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Seaborn (imported, though not used in this script)

📊 Workflow Summary
Data Loading:

Load the dataset using Pandas.
Extract relevant features: Annual Income (k$) and Spending Score (1–100).

Preprocessing:

Standardize the features using StandardScaler to normalize the data for better clustering performance.

Elbow Method:

Use Within-Cluster-Sum-of-Squares (WCSS) to determine the optimal number of clusters.
Plot the WCSS curve to identify the "elbow" point.

K-Means Clustering:

Choose n_clusters = 5 based on the elbow method.
Apply K-Means and assign cluster labels to customers.

Visualization:
Plot the clustered data using different colors to represent different customer segments.


