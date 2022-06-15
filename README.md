# Amazon_Vine_Analysis
# Overview of the analysis: Explain the purpose of this analysis.
I’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. In this project, I pick amazon_reviews_us_Video_Games and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 
# Results
### How many Vine reviews and non-Vine reviews were there?
the vine reviews are 94 and non vine are 40,471
### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
the vine reviews are 48 and non vine are 15663
### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 star
the vine reviews are 51.1 and non vine are 38.7
# Summary: the percentage of paid reviews vs un paid reviews are similar so the program does not show any bias
