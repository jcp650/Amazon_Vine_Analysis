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
- Here is the percentage of 5 star ratings for vine and non-vine reviews;
  - Vine: 56.67%
  - Non-vine: 56.72%

## Summary
