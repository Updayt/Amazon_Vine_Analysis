# Amazon_Vine_Analysis

## Overview of the analysis
To determine if there are any bias toward favorable reviews from the Amazon Vine program. The Amazon Vine Program is a program where amazon customers are sent products and required to leave a review. Amazon Vine program members are the most trusted reviewers on Amazon, according to Amazon on their website. 

## Resources
Data:
- [Link to Data](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)

Software – AWS, PySpark, PgAdmin, SQL

## Results

Vine Data:

![paid1](https://github.com/NickFoley47/Amazon_Vine_Analysis/blob/main/Pics/paid1.PNG)

Non-Vine Data:

![unpaid](https://github.com/NickFoley47/Amazon_Vine_Analysis/blob/main/Pics/unpaid.PNG)

-	Vine reviews: 94
-	Vine total reviews that were 5-stars: 48
-	Vine percentage for 5-star reviews: 51.1%
-	Non-Vine total reviews: 40,471
-	Non-Vine reviews that were 5-stars: 15,663
-	Non-vine percentage for 5-star reviews: 38.7%

## Summary
There is a bias toward 5-star reviews compared to Vine reviews to Non-Vine reviews. Vine percentage 5-star reviews were 51.1% and the non-vine 5-star reviews were 38.7%. That is a 12.4% difference between Vine reviews and Non-Vine reviews. Amazon vine reviewers are customers who leave a lot of reviews, this can cause customers to leave random reviews so they can receive free gear. This can cause the user to have a bias and leave 5-star reviews for every product. Another analysis I would like to conduct is determine by user how often a vine member leaves 5-star reviews for products they receive.  
