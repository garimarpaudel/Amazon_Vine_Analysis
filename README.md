# Amazon_Vine_Analysis

## Overview of Analysis:
In this project, we had access to approximately 50 datasets. I have picked a data set from amazon reviews for kitchen products.
The analysis used PySpark to perform ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin. Also, PySpark was used to determine if there is any bias toward favorable reviwes from Vine members in the dataset.

## Results: 

![image](https://user-images.githubusercontent.com/108683284/211970536-6a0dc644-c374-45f1-a10e-1afacc50d465.png)


### How many Vine reviews and non-Vine reviews were there?

There were 1207 Vine reviews and 97839 non-Vine reviews in total.

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were 509 5-star Vine reviews and 45858 5-star non-Vine reviews in total.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

42.17 % of Vine reviews were 5-stars and 46.87 of non-Vine reviews were 5-stars.

## Summary: 
In the data set, 42.17 % of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 46.87 %.
What these numbers suggest is that there is not strong bias toward five-star reviews from paid Amazon Vine reviewers. This conclusion could be further examined by looking at the distribution of all star-levels across paid and unpaid reviews.

