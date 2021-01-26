# Amazon_Vine_Analysis

## Overview
This project entails analyzing amazon product reviews of musical instruments to determine if there is bias between paid and unpaid reviews. First, the Amazon reviews were sourced from an Amazon S3 repository. Next, the reviews were cleaned and sorted in dataframes towards the goal of matching the file structures to a pgadmin database. Next, the data was loaded into the database using pyspark in a google colaboratoty notebook. After, a new colaboratory notebook was created to analyze whether or not paid reviews are biased.

## Results

- Here is the breakdown of vine and non-vine reviews:
  - Vine reviews: 60
  - Non-vine reviews: 14,477
- Here is the amount of 5 star reviews for vines and non vines:
  - 5 star vine reviews: 34
  - 5 star non-vine reviews: 8212
- Here is the percentage of 5 star ratings for vine and non-vine reviews:
  - Vine: 56.67%
  - Non-vine: 56.72%

## Summary

According to these results, there is no positivity bias between vine and non-vine reviews. The percentage of five star reviews for vine and non-vine reviews are nearly the same. In other words, the difference between the two percentages is not statistically significant. Further, the number of vine and non-vine reviews are significantly different, with non-vine reviews being over 241 times as prevalent as vine reviews. If the number of vine reviews and non-vine reviews were more similar, it would be more likely that there was positivity bias.
Another test that could benefit this analysis is comparing the numbers and percentages of five star reviews of vine and non-vine reviews for multiple different product categories. If the number of votes and percentage of five star reviews in other product categories were similar to the number of votes and percentage of five star reviews in the musical instruments category, then the seemingly small difference would be more statistically significant. 
