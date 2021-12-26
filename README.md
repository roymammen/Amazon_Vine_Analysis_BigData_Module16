# Amazon_Vine_Analysis_BigData_Module16
Overview and Purpose:
  Analyze Amazon reviews written by members of paid Amazon Vine programs.
  
  Access 50 datasets each one contains reviews of specific product.
  
  Pick one dataset and use PySpark to perform ETL process to extract the datast, transform the data connect to an AWS RDS interface.
  Finally load the transformed data into pgAdmin.
  Use Pyspar, Pandas or SQL.
  
Result:
  Two different daasets were accessed 
  ETL performed and connected to PgAdmin to load trasnformed data in Google Colabs to pgAdmin which is connected to AWS server.
  
  Images are captured to display pgAdmin local results.
  
  
Summary:
  With the available dataset used link listed below
  https://s3.amazonaws.com/amazon-reviews-pds/tsv/sample_fr.tsv       
  Total filtered votes greater than 20 gave 0 results
  Hence switched to a value comparision greater than 1. (Criteria : At least there was one user)
  With this filter criteria, also the filter of vine users were 0
  There was an obvisou bias towards non vine users. Which is the reault of analysis.
  I am pretty sure, I did not make any mistakes after several reviews

  
