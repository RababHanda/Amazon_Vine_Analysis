# Amazon_Vine_Analysis

## Overview of Project
This project analyzes the reveiws on furniture products provided by Amazon Vine

### Purpose

**Analytical:** The project analyzes the reviews left by paying and non-paying members on furniture products, to see if the rating depends on the type of customer giving it. 

**Technical:** The project utilizes Google Colaboratory to pull data from Amazon's S3


## Results

It is important to compare the breakdown of reviews voted helpful with all reviews to understand the customer perception and bias in the data. 

<p align="center"><span class="emphasized"> Table 1. Summary of "Helpful" Votes </span></p>
<p align="center">
<img src="/Resources/helpful_summary_df.png" width="60%" height="30%">
</p>

<p align="center"><span class="emphasized"> Table 2. Summary of All Votes </span></p>
<p align="center">
<img src="/Resources/all_summary_df.png" width="60%" height="30%">
</p>


#### 1. How many Vine reviews and non-Vine reviews were there?
In total there are 792,113 reviews, of which 2,775 are Vine and 789,338 are non-Vine. 

However, among the "voted" reveiws, there here are 130 Vine reviews and 16,820 non-Vine reviews

#### 2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were 1,356 5-star Vine reviews and 446,360 5-star non-Vine reviews

#### 3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Only 0.17% of the total Vine reviews are rated 5 stars, whereas 56.35% of all non-Vine reviews are rated 5 stars. 

## Summary

1. The majority of reviews for Furniture product are almost nothing or lower results from Vine participants: 99.6% are Non-Vine.
2. And overall of all 5 Star reviews are also the same as the Furniture, all are from Vine participants: 99.7% of all 5-star reviews are non-Vine.
3. But we need to highlight that not all of the 5 Star reviews are coming from Vine participants.
