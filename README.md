# Customer Segmentation using K-Means Clustering in R
This project demonstrates how to perform customer segmentation using K-Means Clustering in R. It uses unsupervised learning to group customers based on common characteristics — enabling better business decisions and targeted marketing strategies.

## Tools & Technologies Used
R	Programming language
RMarkdown / Jupyter Notebook	Notebook-based analysis in .ipynb format
ggplot2	Data visualization
cluster	Clustering techniques
library purrr 
Lloyd algorithm for k-means clustering



## Problem Statement
Businesses often need to understand different customer types to tailor products, services, and marketing strategies. This project uses K-Means Clustering to segment customers based on their:

Annual Income

Spending Score

These features help identify valuable customer groups such as:

High-value customers

Budget-conscious shoppers

Low-engagement segments

## Dataset Details
Name: Mall Customers Dataset

Source: Public (Kaggle / UCI ML Repo)

Features:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

## Workflow
Data Import and Cleaning

Load dataset using read.csv()

Check for missing values

Exploratory Data Analysis (EDA)

Visualize distributions (bar plots, histograms)

Analyze relationships using scatter plots

Feature Selection

Select relevant features (Annual Income, Spending Score)

Elbow Method

K-Means Clustering

Apply k-means with chosen k

Assign cluster labels

Cluster Visualization

Plot clusters using fviz_cluster() and ggplot2

Interpret different groups based on income and spending behavior

##  Results & Insights
Optimal number of clusters found to be 5 using Elbow Method.

Key customer segments:

🟢 High income + high spending (Premium customers)

🔵 Low income + low spending (Budget customers)

🟡 High income + low spending (Under-engaged potential)

These groups help design targeted campaigns and improve business KPIs.


## Future Work
Add more features like Age, Gender, Purchase Frequency for deeper segmentation.

Apply Hierarchical Clustering for comparison.

Build a Shiny dashboard for interactive visualization.

Integrate RMarkdown to auto-generate reports.

##  Sample Visualization
You’ll find visual outputs like:

📉 Elbow Method Plot

🧭 Cluster Plots

📊 Cluster-wise interpretation using colors and centroids

##  Author
Vishal Maurya
Metallurgical & Materials Engineering | Data Science Enthusiast
📧 vishal.gusknp2022@gmail.com
