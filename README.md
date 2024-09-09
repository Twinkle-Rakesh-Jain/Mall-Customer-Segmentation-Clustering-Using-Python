# Mall-Customer-Segmentation-Clustering-Using-Python

![image](https://github.com/user-attachments/assets/b664495e-30af-49be-a09c-f28962c12a30)


## Project Description:
The goal of this project was to assist the marketing team in understanding the target customers better and to design tailored campaigns for different customer segments. The task involved segmenting mall customers into distinct groups based on age, annual income, and spending score. By identifying these customer clusters, the marketing team could develop customized strategies that cater to the unique needs of each group, improving campaign efficiency and overall customer satisfaction.

## Objective:
To perform customer segmentation by analyzing demographic and behavioral data using the K-Means clustering algorithm, enabling targeted marketing campaigns for the identified customer segments. The key objective was to divide the market into subsets based on customers' age, income, and spending score.

## Project Execution:
### 1.Data Preprocessing & Exploration:
The dataset containing 200 customers' details (age, gender, annual income, and spending score) was imported and analyzed using Python.
Univariate and bivariate analyses were performed to understand the distributions and relationships between different variables (Age, Annual Income, and Spending Score). Various visualizations (scatter plots, box plots, distribution plots) were used to identify patterns.

### 2.K-Means Clustering:
The K-Means algorithm was employed to segment the customers. The Elbow Method was used to determine the optimal number of clusters for different features.
Two clustering approaches were used: univariate (clustering based on income) and bivariate (based on both income and spending score).

### 3.Cluster Analysis:
The characteristics of each cluster were examined to understand the typical profile of customers in each segment, such as income ranges, spending behaviors, and age distribution.

### 4.Summary Statistics & Visualizations:
Clusters were analyzed using summary statistics (mean and distribution across clusters). These were visualized using pair plots, scatter plots, and heatmaps.

## Key Insights and Analysis:
### 1.Univariate Clustering:
K-Means clustering based solely on Annual Income divided customers into 3 main income groups:
![OptimalClusters_UnivariateAnalysis](https://github.com/user-attachments/assets/1d835a7f-b501-47d8-84a5-e17010d20830)

<img width="807" alt="Univariate Clustering Analysis" src="https://github.com/user-attachments/assets/545e4364-e182-436f-9a52-df919f247048">


### a.Low-income group (Cluster 0): 
Primarily younger customers with an average income of around $33K.

### b.Middle-income group (Cluster 1): 
Customers with incomes around $67K.

### c.High-income group (Cluster 2): 
Wealthier customers with an income nearing $100K.

### Bivariate Clustering:
K-Means clustering based on Annual Income and Spending Score revealed 5 distinct customer segments:

![OptimalClusters_BivariateAnalysis](https://github.com/user-attachments/assets/aa82a9b0-71cf-4587-9f52-414ade1d8aa5)

<img width="613" alt="Bivariate Analysis" src="https://github.com/user-attachments/assets/f77a8adc-23a4-487b-a595-28e81bfaf776">

![clustering_bivariate](https://github.com/user-attachments/assets/21a1d7b6-650b-4fa7-a1f1-e35efdc30328)


### Cluster 0:
High-income, low-spending males.
### Cluster 1: 
Low-income, high-spending younger females.
### Cluster 2: 
Middle-income, moderate spending scores, balanced age and gender.
### Cluster 3: 
High-income, high-spending young adults, balanced gender.
### Cluster 4: 
Low-income, low-spending older males.

### Analysis & Interpretation:
### 1. Cluster 3(high-income and high-spending customers) 
Represents a prime target for premium product marketing. These individuals are likely to respond to exclusive offers and high-end products.

### Cluster 1 (low-income but high-spending customers) 
Consists of younger female shoppers who may be more receptive to discounts and loyalty programs.

### Cluster 0 (high-income, low-spending) 
Indicates a older males group that, despite their wealth, tends to spend conservatively. A campaign strategy involving personalized engagement and value-driven offers might be more effective for this group.

### Cluster 4 (low-income, low-spending) 
Likely represents a budget-conscious group that may respond well to cost-effective and essential product marketing.

## Project Summary:
This project employed K-Means clustering to segment mall customers based on demographic (age, gender) and behavioral (income, spending score) data. The analysis identified five distinct customer clusters, each with unique characteristics in terms of age, income, gender, and spending behavior. Understanding these clusters allows for more tailored marketing strategies, with a focus on premium products for younger females, budget-conscious options for older males, and mid-tier strategies for middle-aged customers. The insights derived from this segmentation can be leveraged by the marketing team to improve campaign targeting and increase customer engagement and retention.
























