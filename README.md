# AI_Powered_Customer_Segmentation

Overview

This project performs customer segmentation using the K-Means clustering algorithm. The objective is to group customers based on their annual income and spending score to understand purchasing behavior and support business decision-making such as targeted marketing and personalized offers.

Dataset

The dataset contains the following fields:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

The features used for clustering in this project are:

Annual Income (k$)

Spending Score (1–100)

Approach

Data selection and preprocessing

Determining the optimal value of K using the Elbow Method

Training K-Means on the selected features

Visualizing the clusters and their centroids

Comparing cluster-wise income and spending averages

Predicting the segment for new customer data

Model

The K-Means algorithm is used for unsupervised clustering. The number of clusters selected in this project is 5, based on the Elbow Method.

Example training:

kmeans = KMeans(n_clusters=5, random_state=42)
kmeans.fit(X)

Cluster Interpretation

After training, the customers can be grouped into meaningful segments. Example segment labels include:

Standard Customers

Careful Customers

Target Customers

Careless Customers

Sensible Customers

(Note: Labels may vary based on interpretation)

Visualizations Included

Elbow Method curve

Scatter plot of clusters with centroids

Bar chart of average annual income by cluster

Bar chart of average spending score by cluster

Prediction

The model can predict the cluster of a new incoming customer. Example:

new_customer = np.array([[70, 80]])
predicted_cluster = kmeans.predict(new_customer)[0]

Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-Learn

Project Structure
customer-segmentation.ipynb
README.md
dataset.csv
requirements.txt

Conclusion

Customer segmentation using K-Means provides valuable insights into purchasing behavior and helps businesses optimize marketing and product strategies.
