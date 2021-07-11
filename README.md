# Amazon_Vine_Analysis
# Overview of the analysis
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.
## Purpose of the analysis
The purpose of this analysis was to determine if there was a difference in paid (Vine program) vs. unpaid 5 star reviews given to products in the shoes category. The dataset was filtered to view only 5 star results and reviews that were found to be helpful to the community of 20 or more votes with a ratio of greater than or equal to 0.5 for helpful votes to total votes.
# Results
## How many Vine reviews and non-Vine reviews were there?
## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
# Summary
## The summary states whether or not there is bias, and the results support this statement 