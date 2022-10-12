# Amazon_Vine_Analysis

## Overview of the analysis:
In this exercise we’ve been tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program. The program is a service that allows manufacturers and publishers to receive reviews for their products. We’ll retrieve the products and their reviews to review how the program is functioning.

## Results: 
In reviewing the effectivness of the Vine program we've pulled the data into a postgress database and filtered the data to expose products by their enrollment status

![Vine Enrolled](https://github.com/taxcollecter/Amazon_Vine_Analysis/blob/1b6487e24ac682bd112238512d53fef5194c7421/Resources/FilteredVotesGreater50pctPaid.png)

![Vine Not Enrolled](https://github.com/taxcollecter/Amazon_Vine_Analysis/blob/1b6487e24ac682bd112238512d53fef5194c7421/Resources/FilteredVotesGreater50pctUnPaid.png)

### Findings
--How many Vine reviews and non-Vine reviews were there?
There were 94 vine reviews and 40471 non-Vine reviews.

--How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were 48 vine reviews with 5 stars and 15663 non-vine reviews with 5 starts.

--What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
51.063% of our vine reviews were 5 stars while 38.701% of our non-vine reviews were 5 Starts 

## Summary: 
In reviewing the data highlighting the performance of the vine program, there does appear to be positivity bias towards products that have been enrolled in the Vine program. Though the non-vine products vastly outnumbered the vine enrolled products, we see that the smaller set (vine enrolled) drastically perform better in the number of 5 star reviews.  
