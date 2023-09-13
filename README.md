# Customers Clustering Project 🏢

![](reports/figures/churn_img2.png)

This project has the goal to identify the profile of the most valuable customers to build a loyalty program, based on RFM model.

The RFM model is a customer segmentation technique widely used in marketing that is based on three key metrics:

- Recency: Evaluates how recently a customer interacted or made a purchase. Newer customers receive higher scores.
- Frequency: Measures how often a customer interacts or makes purchases. More frequent customers receive higher scores.
- Monetary Value: Calculates the total amount spent by a customer on purchases. Customers who spend more receive higher scores.

These metrics are used to classify customers into groups based on their individual scores. This segmentation helps companies customize marketing strategies to meet the specific needs of each group, such as Champions (VIP group), At-Risk Customers, New Customers, Loyal Customers, and Low-Value Customers, increasing the effectiveness of marketing campaigns and return on investment.

Data for analysis were made available within the data competitions platform [Kaggle](https://www.kaggle.com/code/cheekonglim/uk-high-value-customers-identification/notebook).

# 1.0 Business Problem
High level Soccer T-shirts is a company that sells second-line branded soccer t-shirts in the outlet model. Having reached the mark of 5000 customers, the marketing team realized that some of them buy high-ticket products, with high frequency, and contribute significantly to the company's revenue. Having identified this opportunity to increase revenue, they decided to create a loyalty program for these customers, called "VIP group". Therefore, they need to create a structure that identifies the profile of the most valuable customers, as well as other customer groups.

Based on the VIP program, the marketing team will take actions aimed at this audience, aiming to increase retention. It will also carry out actions through social networks through targeted advertising, aiming to reach customers with a similar profile, thus increasing the number of customers in the program.

In this sense, the objective is to group the more than 5000 customers into groups by consumption profile, and identify the most valuable customers. In addition, the following business questions must be answered by the marketing area:

- Who are eligible to participate in the Loyals program?
- How many customers will be part of the group?
- What are the main characteristics of these customers?
- What percentage of revenue contribution comes from Loyals?
- What is the expected revenue for this group in the coming months?
- What are the conditions for a person to be eligible for Loyals?
- What are the conditions for a person to be removed from Loyals?
- What is the guarantee that the Loyals program is better than the rest of the base?
- What actions can the marketing team take to increase revenue?

# 2.0 Business Assumptions

## 2.1 Data Description

| Column            | Description                                                                                                                             |
| :---------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| `InvoiceNo`       | Invoice code |
| `StockCode` | Stock code |
| `Description` | Product description |
| `Quantity` | Quantity of products |
| `InvoiceDate` | Invoice date                                                                                                     |
| `UnitPrice`          | Product price |
| `CustomerID` | Customer id |
| `Country` | Country of the purchase |

# 3.0 Solution Strategy

![](reports/figures/mind_map.png)

The strategy uses the CRISP-DS method, which consists of 9 cyclical steps, where at each iteration of the nine steps, the business result is being improved, aiming for increasingly faster deliveries and increasingly more quality and accuracy, thus enabling the teams that will use the developed results have a product that is minimally usable in the first delivery and that is perfected over time.

# 4.0 Insights

## 4.1 Mind Map 

![](reports/figures/mind_map_churn.png)

## 4.2 Top 3 Insights

**Hypothesis 01: 

**TRUE. 
![](reports/figures/age_in.png)

**Hypothesis 02: 

**FALSE. 

![](reports/figures/score_in.png)

**Hypothesis 03: 

**TRUE. 

![](reports/figures/num_in.png)

![](reports/figures/num_in2.png)

# 5.0 Machine Learning 

## 5.1 Techniques and Performance

# 6.0 Business Results

![](reports/figures/cupom_25.png)

![](reports/figures/bss_conclusion.png)

# 7.0 Conclusions

# 8.0 Lessons Learned

- Prioritize tasks and solutions
- Develop solutions in a cyclical way, thus delivering results in a more agile and efficient way
- Managing unbalanced data with Cluster Centroids
- Possibility of agile and professional consultation of predictive data via API

# 9.0 Next Steps

- Respond to new business hypotheses to better understand data and resource relationships and create new hypotheses to verify other resource relationships
- Apply programming techniques to improve the performance of the created solution
- Anticipation of the split between training and testing before data preparation
- Creation of new functionalities to enrich the data, such as consultation via Google Sheets

