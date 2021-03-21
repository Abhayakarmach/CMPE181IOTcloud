# CMPE181IOTcloud

## Intro
This repo is to configure the bigquery to send data to the google collab. The data comprise of clinical parameters about patients and whether they have heart diseases or not. Based on this two different machine learning modules are trained and tested. Also, data analysis is conducted using correlation matrix and pair grid. 

## BigQuery Setup
1. Create an account in Google Cloud Console(GCC)
2. Inside GCC platform:
    - Create a project 
    - Inside the cloud API service enable the BigQuery API
    - Inside the BigQuery, create a dataset in utility-gravity-308207 folder. 
    - Inside the dataset, choose the create table option and upload dataset file which is the heart_records.csv in our case

## Google Collab and BigQuery connection
1. In google collaboratory provide your google cloud credentials for authentication
2. Declare the cloud project ID 
3. Use an SQL query to select the columns and rows of data from the heart_records.csv table

