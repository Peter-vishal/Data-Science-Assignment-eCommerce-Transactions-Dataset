# Data-Science-Assignment-eCommerce-Transactions-Dataset

## Table of Contents
- [Project Overview](Project-Overview)
- [Dataset Description](Dataset-Description)
- [Project Structure](Project-Structure)
- [Exploratory Data Analysis (EDA)](Exploratory-Data-Analysis-(EDA))
- [Lookalike Model](Lookalike-Model)
- [Customer Segmentation](Customer-Segmentation)
- [Results and Discussion](Results-and-Discussion)
- [Conclusion](Conclusion)


## Project Overview

Provide a brief description of the project, its objectives, and the datasets used.

This project involves analyzing eCommerce transaction data to extract meaningful business insights, develop a lookalike model for customer recommendation, and perform customer segmentation through clustering techniques. The analysis utilizes three datasets: Customers.csv, Products.csv, and Transactions.csv.

## Dataset Description

Summarize the contents of each dataset.

- Customers.csv: Contains customer information, including unique identifiers, names, regions, and signup dates.
- Products.csv: Includes product details such as unique identifiers, names, categories, and prices.
- Transactions.csv: Records transaction data, encompassing transaction IDs, customer and product IDs, transaction dates, quantities, total values, and prices.

## Project Structure

Outline the organization of your project files and directories.

- ├──Data
- │    ├── Customers.csv
- │    ├── Products.csv
- │    └── Transactions.csv
- ├──Notebooks
- │    ├── Peter_Task1+EDA.ipynb
- │    ├── Peter_Task2_Lookalike.ipynb
- │    └── Peter_Task3_Clustering.ipynb
- |──Reports
- │    ├── EDA_Report.pdf
- │    └── Clustering_Report.pdf
- ├── Lookalike.csv
- ├── requirements.txt
- └── README.md


## Exploratory Data Analysis (EDA)

Summarize the EDA process and highlight key findings.

The EDA involved data cleaning, visualization, and statistical analysis to understand customer behaviors and product performance. Key insights include:

- Insight 1: Most customers are concentrated in a few regions, suggesting region-specific marketing campaigns 
could be beneficial.
- Insight 2: The top-selling products contribute significantly to revenue, indicating a focus on these items can 
maximize profits.
- Insight 3: Monthly sales trends show clear seasonality, offering opportunities for seasonal promotions.
- Insight 4: A small number of products account for a large portion of total sales, emphasizing the Pareto principle.
- Insight 5: Customer retention strategies should be designed for regions with declining sales
...
## Lookalike Model

A lookalike model was built using describe the algorithm or approach, e.g., cosine similarity on customer purchase vectors to recommend similar customers based on their profiles and transaction histories. The model outputs a list of top  similar customers with corresponding similarity scores for each target customer.

## Customer Segmentation

-  Optimal Number of Clusters: 5
-  Davies-Bouldin Index: 0.8836 (indicating well-separated clusters)
-  Silhouette Score: 0.3462 (moderate cohesion and separation)
-  Calinski-Harabasz Index: 150.20 (suggesting good cluster separation)

The clustering results have successfully segmented your customers into 5 distinct groups, each with 
unique characteristics. These insights can be leveraged for targeted marketing, customer 
personalization, and business strategy development. While the clustering is generally good, there 
might be room for refinement through further feature engineering or the application of more 
advanced clustering techniques.

## Results and Discussion

The analysis provides actionable insights into customer behaviors, enabling targeted marketing strategies and personalized recommendations. The lookalike model facilitates customer acquisition by identifying potential high-value customers, while the segmentation analysis aids in tailoring services to distinct customer groups.

## Conclusion


*This project successfully analyzed eCommerce transaction data to derive business insights, develop a customer recommendation model, and segment the customer base. Future work could involve suggestions for improvement or further analysis, e.g., incorporating additional data sources, exploring advanced modeling techniques, etc..*
