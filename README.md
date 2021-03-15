# Amazon_Vine_Analysis
Using PySpark and Postgres to analyze Amazon reviews of shoes.

https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Shoes_v1_00.tsv.gz

## Overview
Selecting and Amazon review and analyzing the data using filters, withColumn and count.
Below is the total votes greater than 20
![Votes greater than 20](https://github.com/AmirO8/Amazon_Vine_Analysis/blob/main/Resources/Votes%20greater%20than%2020.png)

- Vine Reviews: 22
- Non Vine Reviews: 26,971
- 5 Star Vine Reviews: 13 
- 5 Star Non Vine Reviews: 14,475
- % of 5 Star Vine Reviews: 59.09%
- % of 5 Star Non Vine Reviews: 53.67%
![Vine Count](https://github.com/AmirO8/Amazon_Vine_Analysis/blob/main/Resources/Vine%20Count.png)
![Non Vine Count](https://github.com/AmirO8/Amazon_Vine_Analysis/blob/main/Resources/Non%20Vine%20Count.png)
![Percentages](https://github.com/AmirO8/Amazon_Vine_Analysis/blob/main/Resources/Percentages.png)

## Summary

There are only 22 vine reviews for shoes which is small compared to non vine reviews at 26,971. Looking at these numbers you can see the bias towards non vine reviews. We have significantly more non vine reviews which. The 22 vine reviews are a small sample size which may not be sufficient if we were to run a test
