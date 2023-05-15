## Date created
13th May 2023

## Project Title
Data Integration Pipelines for NYC Payroll Data Analytics

## Description
In this project I built data pipelines to move data from Azure Datalake into Azure SQL Database and Azure Synapse Analytics using Azure Data Factory. This project also demonstrates data aggregation and parameterization in the pipeline.

## Files used
* raw csv files (https://drive.google.com/drive/folders/1sFpJ2lFZu45PuwirY_8_sQZ04oGoPIbl?usp=share_link)

## Dataset
The raw dataset consists of employee details with their salary and job title information.

## Data Pipeline Creation Process
1) Upload raw files into Azure Data Lake Storage Gen 2
2) Create an empty table in SQL Database (to be used as sink in the pipeline)
3) Create tables in Synapse Analytics (to be used as sink in the pipeline)
4) Create Linked Services in Azure Data Factory
5) Create Datasets in Azure Data Factory
6) Create Data Flow to move data from datalake to SQL database and Synapse Analytics were built using data flow
7) Create Pipeline for each of the Data Flows
8) Create another Data Flow to aggregate Total Paid data and implement parameter
9) Create Pipeline for the aggregation Data Flow and add in the parameter setting

## List of Resources
- udacity.com

## Credits
* [Udacity](udacity.com)
