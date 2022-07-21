# Amazon-Vine-Analysis

## Overview of the analysis

After creating an Amazon RDS and creating a database and schema for tables in pgadmin, I extracted an s3 dataset file into google colab and inserted the data and columns into these tables by connecting Amazon RDS to our tables. Afterward, I exported the vine table, and I transformed the data to answer specific questions needed for the project.

## Results

* How many Vine reviews and non-Vine reviews were there?

There were 0 vine reviews and 1685 non-vine reviews.

![image](https://user-images.githubusercontent.com/95439555/164913579-481e5ad6-912e-46e7-9bbd-38691d2d25ed.png)

![image](https://user-images.githubusercontent.com/95439555/164913616-e8eedd2e-4aff-4128-ac70-83ef2651d524.png)

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were zero 5 star Vine reviews, whereas there were 631 five-star Vine reviews.

![image](https://user-images.githubusercontent.com/95439555/164913635-0e130ba6-8a74-49be-89a9-1da5a6e8f19c.png)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

The percentage of 5 star Vine reviews was 0, while the percentage of 5 star non-Vine reviews was 0.374.

![image](https://user-images.githubusercontent.com/95439555/164913659-08e49020-cc5f-4bad-85af-bfbe220c4244.png)

## Summary

As it is noticeable, there is a bias regarding the non-Vine reviews since there is no mention of Vine reviews whatsoever. Other analyses could be possible such as figuring out the percentage of purchases that have been verified or not.
