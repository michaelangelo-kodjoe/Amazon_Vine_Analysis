# Amazon_Vine_Analysis

## Overview of analysis
The purpose of this analysis is to analyse Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. A dataset was chosen out a number of dataset and uploaded to the Amazon Web Services(AWS) for analysis using PySpark because of its volume of data. An ETL process was then executed to take the raw data and transform it into usable data in PostgreSQL to further analyse the reviews. Finally the reviews table was extracted into a python pandas dataframe where the results of the final analysis on the review was made which is broken down below.

## Results of Final Analysis
We can ask ourselves these questions from the analyis:

<img width="845" alt="Vine analysis" src="https://user-images.githubusercontent.com/85206793/173260032-acd0edde-dbfd-43cb-9e14-3564e80a07cd.png">

* How many Vine reviews and non-Vine reviews were there?

  From the image above, it can be seen that there was a total of 5808 Vine reviews and 2,261,967 non-Vine reviews
  
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  Out of the 5808 vine reviews, 48 of them were 5 star reviews and  out of the 2,261,967 non-Vine reviews, 15663 were 5 star reviews
 
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  
  51% of vine reviews were 5 stars and 39% of non vine reviews were 5 stars
  
## Summary
According to this analysis, one can say there is a positivity bias because comparing the number of votes for a 5 star review to a the helpful votes seems to be higher. This might indicate that some people might be giving votes for other reasons such as not actually reading and intending to put an honest review.

One further analysis that can be made is to use the helpful_votes to narrow down the accuracy of the total votes. that way we can have a true idea of what the actual total votes is.
