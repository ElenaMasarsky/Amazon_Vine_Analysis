# Amazon_Vine_Analysis
## Overview of the analysis of the Vine program:  
In this project we are going to analize Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.
Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project, we have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products.
We need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.
Next, we use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in our dataset.  

## Results:  


Our final DataFrame shows following results:  
- There are 94 Vine reviews and 40471 non-Vine reviews.  
- There are 48 Vine reviews having 5 stars and 15663 non-Vine reviews having 5 stars.  
- There are 51.0% of Vine members which have 5 stars and 38.7% of non-Vine reviews which have 5 stars.  

## Summary:  

Comparing percentages of 5 stars reviews of  Vine members and non-Vine reviewers we can assume that there might be some but not too strong bias. The difference between Vine and non-Vine members amounts to 11.3%.
Therefore it would be resonable to do additional analysis. For example, additional analysis could be performed on the 1/2/3/4 star reviews to compare results and see if there is any bias.