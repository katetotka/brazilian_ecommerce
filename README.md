# [Brazilian E-commerce](https://www.kaggle.com/olistbr/brazilian-ecommerce)
Brazilian E-Commerce Public Dataset by Olist: 100,000 Orders with product, customer and reviews info

# The context of this dataset
This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. After a customer purchases the product from Olist Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.

# The content of this data
The data is divided into 9 different datasets and 52 columns. In the schema below, it is depicted the way by which the datasets are connected with each other:
![image](https://user-images.githubusercontent.com/99084086/153183648-07f2c85b-c35e-490f-9426-87136d83f024.png)
You can download the datasets from the <b> data explorer </b> section on [kaggle's](https://www.kaggle.com/olistbr/brazilian-ecommerce) website.

# Exploratory Data Analysis
A brief EDA is made on these 9 different datasets by using the open source language R and some of its packages (tidyverse, ggrepel, lubridate). This analysis could also be done by using SQL (as we are talking about tabular datasets that are connected through keys). In this analysis, the following questions are answered:

1. Which is the unique code that made the most orders?
2. Which are the order details from the previous query?
3. Which is the total number of customer purchases per year and month in query 1?
4. In which month the smallest inflow of revenue took place?
5. Which was the monthly income of the company for the recording period?
6. How many customers have declared as location "campinas"?
7. Which product category had the most orders?
8. Which is the total shipping cost of products purchased from rio de janeiro?
9. Which product category that had the best average rating?
