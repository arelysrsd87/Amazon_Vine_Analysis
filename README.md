# Amazon_Vine_Analysis
# Overview of the analysis
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We selected the shoes dataset and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.
## Purpose of the analysis
The purpose of this analysis was to determine if there was a difference in paid (Vine program) vs. unpaid 5 star reviews given to products in the shoes category. The dataset was filtered to view only 5 star results and reviews that were found to be helpful to the community of 20 or more votes with a ratio of greater than or equal to 0.5 for helpful votes to total votes.
# Results
![Vine Review Results](https://github.com/arelysrsd87/Amazon_Vine_Analysis/blob/main/Resources/Results.jpg)
- There were 22 Vine reviews and 26, 987 non-Vine reviews.
- There were 13 Vine reviews that were 5 stars and 14, 475 non-Vine reviews that were 5 stars.
- The percentage for Vine 5-star reviews to total paid reviews was 59.09% and the percentage for unpaid 5-star reviews to total unpaid reviews was 53.63%.
# Summary
The ratio of Vine 5-star reviews to non-Vine 5-star reviews is 1:1, hence there is no positive bias towards Vine reviews. An additional test that could measure bias would be to filter results based on viewing reviews only for verified purchases. This step would further verified the review was left by a true customer of the product.
