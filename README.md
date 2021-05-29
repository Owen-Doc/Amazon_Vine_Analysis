# Amazon_Vine_Analysis
Using Pyspark, AWS, S3, and PostgresSQL to analyze customer reviews from Amazon datasets

## Summary
The purpose of this analysis is to evaluate Amazon customer reviews for musical instruments, and look at the efficacy of the Vine program, where reviewers are compensated for their reviews. I obtained data from an Amazon S3 bucket that catalogues reviews specifically for musical instruments, then used Pyspark to extract, transform and load the data to a Postgres server to be stored. Amazon's reviews are structured uniformly in column names and types, so this analysis could be reused for other category analyses with minimal refactoring, only changing the S3 address that the program extracts the data from. 