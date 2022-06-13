# Amazon_Vine_Analysis

## Overview of analysis
The purpose of this analysis is to analyse Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. A dataset was chosen out a number of dataset and uploaded to the Amazon Web Services(AWS) for analysis using PySpark because of its volume of data. An ETL process was then executed to take the raw data and transform it into usable data in PostgreSQL to further analyse the reviews. Finally the reviews table was extracted into a python pandas dataframe where the results of the final analysis on the review was made which is broken down below.

## Results of Final Analysis
We can ask ourselves these questions from the analyis:

How many Vine reviews and non-Vine reviews were there?
