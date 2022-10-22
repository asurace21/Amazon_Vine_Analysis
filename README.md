# Amazon_Vine_Analysis

## Overview

The purpose of this project is to analyze amazon gift card reviews provided by members of the paid Amazon Vine program. Using PySpark we performed the ETL process to extract the dataset, transformed the data, connected it to an AWS RDS instance, and loaded the transformed data into pgAdmin. Then we used Pandas to determine if there was any bias toward favorable reviews from Vine members. 

Results

How many Vine reviews and non-Vine reviews were there?

There were 0 Vine reviews and 149,087 non-vine reviews

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

0 Vine reviews were 5 stars. 90 non-vine reviews were 5 stars

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

0% of Vine reviews were 5 stars. 25.35% of non-Vine reviews were 5 stars

![Screenshot_20221022_035218](https://user-images.githubusercontent.com/106443196/197361648-a849ff76-81b7-4280-8a71-1d009a0c6b46.png)

## Summary

The results show that no vine users provided reviews on gift cards. More surprisingly, non-vine users who wrote giftcard reviews, only 25% of them rated it as 5 star. This may lead to the bias that the gift cards may not be the most reliable way to attract customers. We would have to further analyze the data to have a better understanding of why that may be the case.

