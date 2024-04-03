# Amazon_Pantry_Product_Ranking
Predicting the Rank of a Product in Amazon Pantry - EDA, Feature Engineering, Regression Models using Lasso and Ridge Regularisation

# Introduction
This paper presents a model for predicting the rank of products in Amazon Pantry using a set of features. The Amazon Review Data (2018), a large crawl of product reviews from Amazon between May 1996 and Oct 2018, was used for this study. This dataset was authored by Jianmo Ni, from UCSD. The K-cores subset of this dataset, which consists of smaller per-category datasets, was used. Specifically, we selected the "Prime Pantry" subcategory, which contains 137,788 rows (reviews) and 12 columns. Our goal is to investigate the relationship between the rank of a product and its features, including the average rating, total number of reviews, an interaction term of rating and reviews, and crowd puller status. We employ a regression model to analyze the data and estimate the coefficients of the features, which can be used to predict the rank of a product in Amazon Pantry.

Here is the model we will use to rank our products - 

Rank = β0 + β1*(average rating of a product) + β2*(total number of reviews) + β3*(rating*review) + β4(crowd puller) + β5*(price) + ε

# Motivation
The motivation for this project is to understand the factors that contribute to the ranking of products in Amazon Pantry and to develop a model that can predict the rank of a product based on these features. By doing so, we can gain insights into how online retailers can improve the visibility and sales of their products in online marketplaces such as Amazon. This study also contributes to the literature on product ranking and provides practical implications for online retailers looking to optimize their product listings.

