# customer-segmentation-using-clustering

This README file provides a concise overview of the customer segmentation project, detailing the methodology, key findings, and actionable business insights.

## 1. Project Goal
The primary objective of this project was to perform customer segmentation for a mall, using unsupervised machine learning. By applying the K-Means clustering algorithm, the project aims to identify distinct customer groups based on their spending and demographic data, enabling the business to develop targeted marketing strategies.

##  2. Working and Methodology
The project follows a professional data science workflow:

### Data Exploration (EDA): 
The analysis began with in-depth exploratory data analysis to understand the data's distribution and relationships. A key finding from this stage was the visible grouping of customers when plotting Annual Income against Spending Score.

### Optimal Cluster Determination:
The Elbow Method was used to systematically determine the optimal number of clusters. The analysis of the Within-Cluster Sum of Squares (WCSS) plot revealed a clear "elbow" at 5 clusters, which was chosen as the optimal number for segmentation.

### K-Means Clustering: 
The K-Means algorithm was applied with five clusters to group customers. This model effectively partitioned the customer base into five distinct, non-overlapping segments.

### Visualization:
A final scatter plot of Annual Income vs. Spending Score was generated, with each data point colored to represent its assigned cluster. This visualization provides a clear, at-a-glance view of the final segments.

## 3. Business Insights: Actionable Customer Segments
The project successfully identified five unique customer segments, each with a distinct profile and a recommended marketing strategy.

### Frugal Shoppers: (Low Income, Low Spending)

#### Strategy: 
Offer discounts, coupons, and value-based promotions to appeal to their budget-conscious nature.

### Target Customers: (Average Income, Average Spending)

#### Strategy: 
Maintain loyalty and engagement with personalized offers and a tiered loyalty program. This is your core customer base.

### Careful Spenders: (Low Income, High Spending)

#### Strategy:
Drive impulse buys through social media campaigns and limited-time offers on trendy items.

### Responsible Spenders: (High Income, Low Spending)

#### Strategy: 
Attract this untapped segment with premium products, exclusive collections, and a focus on quality over price.

### Elite Spenders: (High Income, High Spending)

#### Strategy:
Implement a VIP program with exclusive access and personalized service to reward their loyalty and high value.


This project demonstrates the power of data-driven decision-making, transforming raw data into a clear and effective business strategy.
