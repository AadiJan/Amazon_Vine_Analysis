# Amazon_Vine_Analysis

## Overview of the Project:
The intent of the project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. For this project, I have used the 'home improvement' project reviews (Link to the dataset: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Home_Improvement_v1_00.tsv.gz)
With the provided datase, I have used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Also, use Python to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results:

* How many Vine reviews and non-Vine reviews were there?
  - 18,371 vine reviews and 20724 non-vine reviews
![image](https://user-images.githubusercontent.com/112893464/213898779-811e90cc-8825-4a39-bdc2-ab0c004e55cb.png)


* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - 18,371 5 star reviews. 
![image](https://user-images.githubusercontent.com/112893464/213898814-e5784eb8-9598-4116-9838-4d085739b4f0.png)

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 49% were vine and 41% were non-vine reviews

![image](https://user-images.githubusercontent.com/112893464/213898849-f02e904e-e37e-4067-b1c6-9aa2f92e3b3c.png)


## Summary:
After performing the analysis, Vine-review program seems to have a higher percentage of 5-star reviews comapred to the non-vine program. 
