# Overview:

The following analysis focuses on the Amazon Vine program that measures the difference between member and non-member participants to determine if there is any bias toward favorable reviews from Vine members. 

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

Having access to approximately 50 different Amazon product datasets, each one contains reviews of a specific product, from clothing apparel to wireless products. 

Using PySpark and performing ETL within a Amazon reviews based on Tools database we have connected the AWS RDS and pgAdmin to determine the differences. 

## Technologies: 
PySpark, Amazon Web Services, Python, Pandas

# Results: 

After running our metrics and creating data frames we have found the following results below.

o	Total Vine reviews = 285

o	Total non-Vine reviews = 31,545

o	Vine 5 Star reviews = 163

o	Non-Vine 5 Star reviews = 14,614

o	5-star Vine review percentage = 57.2%

o	5-star non-Vine review percentage = 46.3%

![Screenshot (100)](https://user-images.githubusercontent.com/81484054/128611876-69b75d08-df10-436f-a48e-289e76084182.png)

![Screenshot (99)](https://user-images.githubusercontent.com/81484054/128611915-a754cb55-13d1-453e-ad01-274708bdf845.png)


# Summary: 

When reviewing our metrics, we have found that there was a 57.2% of 5-star reviews that were based within the Vine program and a 46.3% of 5-star reviews for non-Vine members. With this slight difference the Vine program does show positivity for the Vine members over the non-Vine members. 

One additional result that could support our analysis is gathering the mean of all star ratings, zero through five, to truly measure the percentage of the reviews for Vine and non-Vine members.
