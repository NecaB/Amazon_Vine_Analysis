#Amazon_Vine_Analysis

Overview 

This challenge was to analyze Amazon reviews written by members of a paid Amazon Vine program. This program allows manufacturers and publishers to receive reviews for their products. The analysis was conducted to determine if there was any bias towards favorable reviews from Vine members. 

PySpark was used to perform an ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load and transform data into pgAdmin and calculate the different metrics. Our study focused on reviews from Amazon Watches to analyze and determine the above stated objectives. 

Results 

The following results were derived from the query ran in the Google Colab Notebook environment about the Amazon review of watches.

Number of Reviews 

How many Vine reviews?    47
 <img width="463" alt="image" src="https://user-images.githubusercontent.com/109915684/202356603-cd28bde5-badf-48e7-bdc5-9a09d390c084.png">
 
How many non-Vine reviews? 8326
 <img width="431" alt="image" src="https://user-images.githubusercontent.com/109915684/202356570-1f06c309-685c-410e-8553-53505d8e98f0.png">

Number of 5-star reviews 

How many Vine reviews were 5-stars? 15
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/109915684/202356449-568defa5-9b61-423d-b167-57bfd29fda07.png">

How many non-Vine reviews were 5-stars? 4321
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/109915684/202356401-19bfd304-1a7b-4e06-81b2-a330ba33c96a.png">

Percentage of Reviews 

What percentage of Vine reviews were 5-stars? 32
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/109915684/202356372-a9b778d8-6b16-4308-9dbe-a94668fc7b41.png">

What percentage of non-Vine reviews were 5-stars? 52%
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/109915684/202356344-fcc69ba7-d544-4d04-ad27-be89f6e2d9f5.png">

Summary

In conclusion, there were 47 Vine reviews and 8326 Non-Vine reviews. From those number of reviews 15 of the Vine reviews were 5 star and 4321 of the Non-Vine reviews were 5 star. Overall, approximately 32% of the Vine reviews were 5 stars and the percentage of Non-Vine, 5 star reviews were approximately 52%. This does not imply a positivity bias for the reviews in the vine program on the watches category. 

Recommendations 

I would recommend the following
-	to utilize more datasets to determine if there’s an overall bias in the Amazon Vine reviews program as an analysis of one dataset is not representative of the entire Vine reviews program. 

-	analyze other summary statistics namely, mean mode and median of the star ratings to determine if there’s a bias. 

