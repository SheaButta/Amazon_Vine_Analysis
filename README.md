# Amazon_Vine_Analysis

## Overview 
The purpose of this project is to assist my client with reviewing an Amazon S3 dataset that contains wireless product data.  The client would like my assistance with
using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.  Additionally, I will use PySpark to determine if there is any bias toward favorable reviews from Vine members in this dataset.  I will conclude with a summary of the analysis for my client to submit to their stakeholders.  As always, my analysis followed the data analysis principles of (1) Determine the number of rows and columns; (2) Data types used; and (3) Is the data readable?

__Client Deliverables:__
- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis (README.md)


## Resources
The resouces used for this analysis included;
- AWS Relational Database Service (RDS)
- AWS Simple Storage Service (S3)
- PySpark (ETL)
- PostgreSQL
- pgAdmin


## Results
All sprints were completed as scheduled and I delivered on all client expectations/results. The below images will visualize the expected client results to help summarize if a there was any bias of vine review.

### Deliverable 1: Perform ETL on Amazon Product Reviews

This deliverable required me to create a new database with Amazon RDS (Relational Database Service) and add database tables and data to this database using pgADMIN.  The data was successfully loaded using my PySpark ETL pipleline.

![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/customer.PNG)

![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/products.PNG)

![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/review_id_table.PNG)

![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/vine_table.PNG)


### Deliverable 2:  Determine Bias of Vine Reviews

This deliverable required me to collect and manipulate the dataset to generate various calculations which will help determine bias of vine review.  The various calculated parts are identified below to help determine the possibility of bias of Vine Reviews.

  _**Number of Vine reviews:**_
  
  ![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/TOTAL_PAID.PNG)


   _**Number of non-Vine reviews**_
   
   ![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/TOTAL_UNPAID.PNG)
   
   
   _**Number of Vine reviews that were 5 stars**_
   
   ![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/TOTAL_PAID_5STAR.PNG)
   
   
   _**Number of non-Vine reviews were 5 stars**_
   
   ![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/TOTAL_UNPAID_5STAR.PNG)
   
   
   _**Percentage of Vine reviews were 5 stars**_
   
   ![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/Percent_PAID_5Star.PNG)
   
   
   _**Percentage of non-Vine reviews were 5 stars**_
   
   ![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/Percent_UNPAID_5Star.PNG)
   
   
## Summary
My client is extremely pleased with the final sprint as we have proven the ability to read JSON and GeoJSON data and most importantly visualize the data using D3 (Data-Driven Documents) and the Leaflet JavaScript library.  










