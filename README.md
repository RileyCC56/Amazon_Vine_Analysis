# Overview:

The following analysis focuses on the Amazon Vine program that measures the difference between member and non-member participants. 

Using PySpark and performing ETL within a Amazon reviews based on Tools database we have connected the AWS RDS and pgAdmin to determine the differences. 

# Results: 

After running our metrics and creating data frames we have found the following results below.

o	Total Vine reviews = 285
o	Total non-Vine reviews = 31,545
o	Vine 5 Star reviews = 163
o	Non-Vine 5 Star reviews = 14,614
o	5-star Vine review percentage = 57.2%
o	5-star non-Vine review percentage = 46.3%

# Summary: 

When reviewing our metrics, we have found that there was a 57.2% of 5-star reviews that were based within the Vine program and a 46.3% of 5-star reviews for non-Vine members. With this slight difference the Vine program does show positivity for the Vine members over the non-Vine members. 

One additional result that could support our analysis is gathering the mean of all star ratings, zero through five, to truly measure the percentage of the reviews for Vine and non-Vine members.
