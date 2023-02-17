# Module 17 Challenge: Amazon Review Analysis with Big Data

## Overview

The purpose of this analysis is to analyze product reviews for the Amazon Vine program. This program allows sellers to guarantee reviews for their products; sellers provide their products to members of the Amazon Vine program, who are required to post reviews on the products. This dataset focuses primarily on Health and Personal Care item reviews. 

This project will leverage Big Data technologies like Amazon Web Services's Relational Database Service and Simple Storage Solution (AWS RDS and AWS S3, respectively). The publically available review data will be extracted, transformed, and loaded using PySpark in a Google Colab notebook. Cleaned datafiles will then be uploaded to the AWS-hosted PostgreSQL database.

## Results

The results of the analysis show that:
Totals:

- Total number of reviews: 5,331,449
- Total number of *helpful* reviews: 121,360
- Total number of 5-Star reviews: 3,358,086
- Total number of *helpful* 5-Star reviews: 74,690
- Total number of Vine reviews = 497
- Total number of Non-Vine reviews = 120,863
- Total number of *helpful* 5-Star Vine reviews = 220
- Total number of *helpful* 5-Star Non-Vine reviews = 74,470

Percentages

- Percent Vine Reviews of *total* reviews: 0.00932%
- Percent Vine Reviews of *helpful* reviews: 0.409%
- Percent 5-Star Vine reviews of *total* Vine reviews: 44.265%
- Percent 5-Star Non-Vine reviews of *total* Non-Vine reviews: 61.615%
- Percent 5-Star Vine reviews of *total* 5-Star reviews: .295%
- Percent 5-Star Non-Vine reviews of *total* 5-Star reviews: 99.705%


## Summary 

The results do not provide strong support for the notion that the Vine review program impoarts positivity bias on reviewers. Vine reviewers gave 5-star feedback 44.3% of the time, while Non-Vine reviewrs gave the same feedback 61.6% of the time. It seems that paid Vine reviewers rated these Health and Personal Care items more harshly than the general population. 

Additionally, the Vine program may not be the best investment for sellers. Vine reviewers make a very small portion of the total number of reviews, and leave a smaller proportion of positive reviews than non-Vine reviewers. 

