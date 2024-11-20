**Customer Segmentation Using K-Means Clustering**
**Project Overview**
Customer segmentation is a critical task in marketing and business analytics that enables organizations to identify and understand different groups of customers. In this project, we use K-Means Clustering, an unsupervised machine learning algorithm, to segment customers based on their Annual Income and Spending Score.

The segmentation helps businesses to:

Personalize marketing campaigns.
Improve customer targeting.
Enhance customer retention strategies.
This project analyzes customer data, applies the K-Means algorithm to find clusters, and visualizes the results to extract actionable insights.
![image](https://github.com/user-attachments/assets/d4f3ef04-6c1c-49b1-a415-966b5ce39408)

Technologies and Tools
Programming Language: Python
Libraries Used:
pandas: For data manipulation and cleaning.
matplotlib and seaborn: For data visualization.
scikit-learn: For applying the K-Means clustering algorithm.
Dataset
The dataset contains information about customers, including:

Annual Income (k$): The yearly income of a customer.
Spending Score (1-100): A score assigned to the customer based on their spending behavior.
Features Used for Clustering
Annual Income: Represents the customer’s income level.
Spending Score: Indicates how much they typically spend.
Project Workflow
Data Preprocessing:

Loaded and cleaned the dataset.
Selected features (Annual Income and Spending Score) for clustering.
Normalized the data (if required).
Applying K-Means Algorithm:

Determined the optimal number of clusters using the Elbow Method.
Applied the K-Means algorithm to segment the customers into clusters.
Identified cluster centroids.
Visualization:

Plotted clusters in a 2D graph with Annual Income on the x-axis and Spending Score on the y-axis.
Highlighted centroids to represent the center of each cluster.
Insights:

Identified and interpreted customer groups based on spending patterns and income levels.
Results
The K-Means algorithm segmented customers into 5 distinct groups:

High-Income High-Spenders (Premium Customers).
High-Income Low-Spenders (Savings-Oriented Customers).
Low-Income High-Spenders (Impulsive Shoppers).
Low-Income Low-Spenders (Budget-Conscious Customers).
Moderate-Income Average-Spenders (Balanced Shoppers).
Each cluster represents a unique customer segment, enabling targeted business strategies.
