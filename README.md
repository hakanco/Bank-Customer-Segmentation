# Bank-Customer-Segmentation
## Business Case & Problem Statement
If there is enough data about customers, data science can be applied for market segmentation. In this case study, the bank has extensive data on their customers for the past 6 months. As a marketing team at the bank we will divide customers into distinctive groups to launch a targetted ad marketing campaign. Process of grouping customers based on their interactions with the business and having some common characteristics. In most cases, interactions depend on their purchase behaviors. 
# Data
Explanation of each independent features
1. CUSTID: Identification of Credit Card holder 
2. BALANCE: Balance amount left in customer's account to make purchases
3. BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
4. PURCHASES: Amount of purchases made from account
5. ONEOFFPURCHASES: Maximum purchase amount done in one-go
6. INSTALLMENTS_PURCHASES: Amount of purchase done in installment
7. CASH_ADVANCE: Cash in advance given by the user
8. PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
9. ONEOFF_PURCHASES_FREQUENCY: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
10. PURCHASES_INSTALLMENTS_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
11. CASH_ADVANCE_FREQUENCY: How frequently the cash in advance being paid
12. CASH_ADVANCE_TRX: Number of Transactions made with "Cash in Advance"
13. PURCHASES_TRX: Number of purchase transactions made
14. CREDIT_LIMIT: Limit of Credit Card for user
15. PAYMENTS: Amount of Payment done by user
16. MINIMUM_PAYMENTS: Minimum amount of payments made by user  
17. PRC_FULL_PAYMENT: Percent of full payment paid by user
18. TENURE: Tenure of credit card service for user
# Step by Step Methodology:
1.  Import Libraries and Dataset
2.  Data Clean Up
3.  Exploratory Data Analysis & Feature Selection
4.	Scale the Data Using ‘StandardScaler’
5.	Generation of Clusters using K-means 
6.	Generation of Clusters using Hierarchical Agglomerative 
7.	Inspection of Clusters using Principal Component Analysis 
8.  Generation of Clusters using AutoEncoders
# Conclusion
Optimal number of cluster is found by applying K-means Algorithm with elbow-method, and applied K-Means k=8 number of clusters. I have also tried autoencoders to cluster customers using encoded data with 10 features by dividing customers into four distinctive groups.   
