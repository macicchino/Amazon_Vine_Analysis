# Amazon_Vine_Analysis
Module 17 Challenge - ETL with PySpark, AWS, PostGres, and Google Colab


## Overview of the analysis: Explain the purpose of this analysis.

The purpose of the analysis is to help Jennifer with analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

So we want to analyze the impact of vine reviews on overall product reviews. This way, we can see if the Amazon Vine program has a positive impact on product reviews. 

## Results: 
### Using bulleted lists and images of DataFrames as support, address the following questions:

 1. How many Vine reviews and non-Vine reviews were there?
   - There were 103 total Vine reviews.
   - There were 37,441 total non-Vine reviews. 

 2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
   - There were 55 total Vine 5-Star reviews.
   - There were 19,736 total non-Vine 5-Star reviews.

 3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
   - 53.4% of Vine Reviews were 5 Stars
   - 52.7% of non-Vine Reviews were 5 Stars

## Summary: 
### In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

 - As we can see for outdoor products on Amazon, products with Vine reviews have a slightly higher % of 5 stars reviews with 53.4% compared to 52.7% of non-Vine reviewed products. 

- An additional analysis would be to see the impact across different products lines. We could use the same code to perform an anlysis on different product sectors then compare the vine review impact across different product lines. If we wanted to continue an analysis with the same dataset, we should see if vine has a similar impact on low star ratings. Because we only filter for better reviews, we should see if vine has an impact say for 1-star reviews. 


## Image Support:

Provided below is an number of snapshots from the analysis. 

![dev_1](Images/Dev1_DataFrame.png "Dev 1 Image")



