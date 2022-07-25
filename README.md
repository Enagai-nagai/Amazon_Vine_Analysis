# Amazon_Vine_Analysis


## Overview of the analysis: Explain the purpose of this analysis.
Our company "SellBy" provides products to Amazon Vine members. We will analyze the reviews by Amazon Vine members to see what they like/dislike about the product and figure out how we can improve the sales on Amazon platform.

This time, we used this url 
https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Sports_v1_00.tsv.gz


## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

* How many Vine reviews and non-Vine reviews were there?
![image](https://user-images.githubusercontent.com/99149443/180699499-6930973b-9bb0-4863-9a1c-f879ce622c1f.png)
There were much more reviews by Non-Vine users.

## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
### Among everyone
![image](https://user-images.githubusercontent.com/99149443/180700373-20735be4-1743-4638-8679-f8a45fef4beb.png)

### Among Vine users
![image](https://user-images.githubusercontent.com/99149443/180700581-d5db2916-ebeb-4e5b-b3c3-6197e7e8867c.png)

### Among Non-Vine users
![image](https://user-images.githubusercontent.com/99149443/180700663-6e76235e-8e36-4fbe-b44d-bfbf24a3d28c.png)


## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* Among Vine users: 44.4%
* Among Non Vine users: 62.7% 

## Summary: 
* There are way more reviews by Non-Vine users. As the number of Vine Users is limited, analyzing only Vine users may cause bias on the results.
* Among Non Vine users, the % of those who rated 1 is higher than that of Vine users. We should look into what is causing this trend.
