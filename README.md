# UTSA 22: Big Data ETL

## Background
### This project involves performing ETL (Extract, Transform, and Load) on two Amazon customer review datasets. The goal is to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal is to use PySpark or SQL to perform a statistical analysis of selected data.

## Project Setup
#### - Create a new repository for this project called "Big-Data-ETL". Do not add this homework to an existing repository.
#### - Clone the new repository to your computer.
#### - Upload the part_one_starter_code.ipynb into Google Colab and create a duplicate of this file.
#### - Explore the Amazon Reviews datasets and pick two datasets to perform ETL.

## Instructions
#### 1. Rename each part_one_starter_code.ipynb file according to the dataset you are using. For example, if you are going to use the Video Game reviews file, rename file, part_one_video_games.ipynb. Repeat the process for the duplicate file you created in Step 2.
#### 2. Extract the Data:
#### - Read in each dataset using the correct header and sep parameters.
#### - Get the number of rows in the dataset.
#### 3. Transform the Data:
#### - For each dataset use the schema.sql file located in the Resources folder of the Starter_Code.zip file to create the four DataFrames.
#### - Create the "review_id_df" DataFrame with the appropriate columns and data types.
#### - Create the "products_df" DataFrame that drops the duplicates in the "product_id" and "product_title" columns.
#### - Create the "customers_df" DataFrame that groups the data on the "customer_id" by the number of times a customer reviewed a product.
#### 4. Load the Data into an RDS Instance:
#### - Export each DataFrame into the RDS instance to create four tables for each dataset.

## Conclusion
### This project is designed to challenge your ETL skills by working with large datasets and performing data transformation in the cloud. By following the instructions, you will be able to extract, transform, and load two Amazon customer review datasets into an RDS instance.
