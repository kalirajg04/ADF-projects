# ADF projects
This repository contains labs and end-to-end projects that I have done on Azure Data Factory. 
Reference for the pipelines.
Please check it out!

1. Excel-To-SQL-pipeline-using-array

   Using this pipeline, we copy the data from an excel file containing multiple sheets to the SQL database. 
   The multiple sheets are taken iteratively. The For-Each activity iterates over the sheet names stored as an array variable.

   Check out the youtube link for the complete process
   
   https://youtu.be/BMc_K9EmwZ0 

2. Excel-To-SQL-pipeline-using-lookup

   Using this pipeline, we copy the data from an excel file containing multiple sheets to a SQL database.
   The multiple sheets are taken iteratively. The For-Each activity iterates over the sheet names stored in a table in the SQL database.

   https://youtu.be/Ikjlk12Na3I

3. SCD_type_1_data_flow_pipeline

   Using this pipeline, we copy data from an Azure blob storage to a SQL database using Slowly Changing Dimension 1, that is, 
   the new data overwrites the existing data. To incorporate this logic into the pipeline, we use the data flow task.
   
4. Send_mail_on_fail.txt

   In this pipeline, we will send a mail using a logic app to alert about pipeline failure.
   
5. SqlDb_to_Blob_delta_copy.txt 

   Using this pipeline, we will incrementally copy the data from a SQL database table to a blob storage using a watermark value. 
