# Amazon-Reviews-ETL
## Teodor Anderson

## Overview of Analysis
 Using Pyspark, Postgres and an AWS RDS instance, my task is to extract data from an Amazon reviews dataset including paid reviews, extracting and wrangling that data with PySpark, and uploading the transformed data to pgAdmin to calculate analyses. 
 
 ## Results
 
 ![image](https://user-images.githubusercontent.com/116928193/229266655-85ea3509-5eec-4a70-b047-aa98ceadc487.png)
 
 * The total amount of paid reviews was 94
 * The total amount of unpaid reviews was 40,471
 
 ![image](https://user-images.githubusercontent.com/116928193/229266811-76da67f0-c858-4fd8-b419-91b236833f96.png)
 
 * The total amount of 5 stars paid reviews was 48
 * The total amount of 5 stars unpaid reviews was 15,663
 
 ![image](https://user-images.githubusercontent.com/116928193/229266853-063f0c9f-f4aa-42ba-8bf0-b302a897d016.png)

* The percentage of 5 stars reviews that were paid was 51.06%
* The percentage of 5 stars reviews that were unpaid was 38.70%

## Summary
 After reviewing the analysis, we can conclude that the Amazon paid reviews program show some bias when giving 5 stars, with a 13.36% more likely hood to provide a 5 star review over people who were not paid
 
 Another analysis we could do is add a column to the original data set of how much the reviewer was paid, and analyize how much higher the stars were compared to their pay
