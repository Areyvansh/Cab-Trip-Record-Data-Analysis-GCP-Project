# Cab-Trip-Record-Data-Analysis-Using-ETL-MAGE

## Introduction
The goal of this project is to perform Data Analytics and find insightson Cab Trip record data using various tools and technologies, including GCP Storage, Python, VM Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

## Architecture
![Architecture Diagram](https://github.com/Areyvansh/Cab-Trip-Record-Data-Analysis-GCP-Project/blob/main/architecture.jpg)

## About Dataset
The primary source of data for this project is the Cab Trip Record Data of year 2016 of NYC Taxi and Limousine Commission data obtained directly from their data sharing platform. This dataset includes detailed information about individual trips, such as trip duration, pickup and drop-off locations, fare amounts, etc.

## Tools and Technology Used
Programming Language:
  1. Python

GCP Services:
  1. AGoogle Storage
  2. VM Compute Instance
  3. BigQuery
  4. Looker Studio
   
## Data Model
![Data Model Diagram](https://github.com/Areyvansh/Cab-Trip-Record-Data-Analysis-GCP-Project/blob/main/data_model.jpeg)

## Project Execution Flow
1. Load Data in Cloud Storage
2. Create a VM Instance and Configure it
3. Run SSH
4. Install Mage and all the required packages on it
5. Create an ETL Pipeline using Mage
6. Export the Data to BigQuery
7. Perform Sql Analysis using BigQuery
8. Create an Analytic Table
9. Visualise the insights on Looker Studio 
