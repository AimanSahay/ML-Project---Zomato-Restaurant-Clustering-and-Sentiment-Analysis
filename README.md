# Zomato Restaurant Clustering and Sentiment Analysis

This project focuses on two key aspects: **Clustering** and **Sentiment Analysis**.

**Data Preprocessing:** Our initial steps involved checking for missing and duplicate values in both datasets. We handled missing values by imputation or removal based on the context of the data. Additionally, we standardized column texts and extracted relevant information into separate columns to facilitate analysis. We ensured consistency in data types across columns for efficient processing.

**Exploratory Data Analysis (EDA):** The EDA phase was crucial in understanding the underlying patterns and trends within the data. Visualizations, including histograms, box plots, violin plots, scatter plots, bar plots helped identify relationships between different attributes. We also converted raw numerical values into meaningful categories to enhance interpretability.

**Sentiment Analysis:** We performed sentiment analysis on the reviews data. We cleaned the review text, calculated sentiment scores using NLP techniques, and visualized positive and negative sentiments for each attribute. This analysis offered valuable insights into customer perceptions and preferences, allowing restaurant owners to make informed decisions to improve customer satisfaction.

**Feature Engineering and Selection:** To prepare the data for clustering analysis, we utilized techniques such as multilabelbinarizer to encode categorical features. Feature selection was performed to identify the most important features contributing to the variability in the dataset. This step aided in reducing dimensionality and improving the efficiency of clustering algorithms.

**Clustering Analysis:** We applied both **KMeans** and **agglomerative hierarchical clustering** algorithms to identify natural groupings within the data. To determine the optimal number of clusters, we utilized the elbow curve, silhouette score, and dendrogram analysis. 

**Cluster Analysis:** After assigning clusters to the data points, we conducted detailed cluster analysis to understand the characteristics and attributes associated with each cluster. This analysis involved examining the average values of different features within each cluster and identifying distinctive traits. Visualizations, heatmaps and scatter plots, provided insights into the composition and distribution of clusters.

As a result of the analysis, **6 clusters** were identified as most optimal dividing the restaurants into appropriate categories. These insights can help establishments gain a deeper understanding of customer behavior and preferences, ultimately enhancing the dining experience and driving business success.
