# Instacart Market Basket Analysis| Snowflake & Tableau

# Overview
The primary goal of this project was to build a data warehouse using Snowflake that can be utilized for a variety of different purposes.

# Technology
<li>Python</li>
<li>Snowflake</li>
<li>Amazon S3</li>
<li>Tableau</li>

# Architecture
<img width="1151" alt="image" src="https://github.com/claydoers/Instacart-data-pipeline-analysis-project/assets/109707159/536e78c0-9f5a-430f-9f88-05101b8571b4">

# Process
<ol type="1">
  <li>Upload raw data to S3 bucket</li>
  <li>Create database and Schema in Snowflake</li>
  <li>Configure access so that Snowflake can connect to AWS</li>
  <li>Create tables for each of the respective Instacart raw csv files</li>
  <li>Write automated script to copy raw data from S3 into each of the tables</li>
  <li>Identify different data types and characteristics to determine which fact and dimension tables we will need to create</li>
  <li>Use Python/Pandas to create data frames to create fact and dimension tables in Snowflake and define primary and foreign keys to create key relationships among the different tables</li>
</ol>


# Dataset
This dataset is a relational set of files describing customers' orders over time. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. For each user, we provide between 4 and 100 of their orders, with the sequence of products purchased in each order. We also provide the week and hour of day the order was placed, and a relative measure of time between orders.

https://www.kaggle.com/c/instacart-market-basket-analysis

# Data Model
<img width="760" alt="image" src="https://github.com/claydoers/Instacart-data-pipeline-analysis-project/assets/109707159/013848ab-5329-4035-8a76-5e3329138ed3">

# Simple Tableau Dashboard Example
![image](https://github.com/claydoers/Instacart-data-pipeline-analysis-project/assets/109707159/bfb12a32-2e01-4659-bb4f-7d352d04ad6b)

