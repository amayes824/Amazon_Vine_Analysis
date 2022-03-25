# Amazon_Vine_Analysis

## Overview of the analysis:
- In this project I have picked a data set from amazon reviews regarding video games and used Pyspark to perform the ETL process by extracting the data, transforming the data and connecting to the database that was generated for me through the AWS webserver. With the reviews my goal is to try and determine if there is favorable review bias from the Vine members of our data set.

## Results: 

## How many Vine reviews and non-Vine reviews were there?
- There were a total of of 4,291 vine reviews in our dataset, and 40,471 non-vine reviews in the complete dataset.
<img width="1406" alt="nonvne" src="https://user-images.githubusercontent.com/67278193/98488023-cbceda00-21f4-11eb-8f84-271b002ea5af.png">

## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- In the data set their was a total of 15,711 5-star reviews
- 15,663 of the 5-star reviews were non-vine

## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 38.2% of the five_star reviews were vine
- 38.9% of the five_star reviews were non-vine
<img width="1361" alt="Screen Shot 2020-11-08 at 6 59 01 PM" src="https://user-images.githubusercontent.com/67278193/98488026-cec9ca80-21f4-11eb-96ee-4aad73f98509.png">

## Summary: 
-After I had come up with my analysis there does not appear to be any sort of positivity bias because the percentages shown above are very similar at 38%. To conclude the analysis the vine program does not show any bias.
