# Movies-ETL

## Overview of the project

This project prepares movie data from different sources to present in a hackathon where the data will be used by hackathon participants to perform analysis. The data has been collected from kaggle and wikipedia in csv (Comma Seperated Value) and json (JavaScript Object Notation) formats respectively. The movie data is cleaned and processed into a database so that it can be easily accessed during the hackathon.

### Purpose

The purpose of the project is to prepare the movie datasets for use in the hackathon by using the ETL (Extract, Transform, Load) process. The data is stored in the database after being cleaned and proccessed for use.

## Results

In this project three datasets were collected:

1. wikipidea-movies.json
2. movies_metadata.csv
3. ratings.csv

The datasets were all cleaned programatically in jupyter notebooks using pandas and other related libraries. Once they were cleaned, and relevant data was kept, they were merged together to form a single movie dataframe. The dataframe was then uploaded to our database as a table along with the processed ratings dataframe. The tables are ready to be used for the hackathon and using SQL we can query the database to extract information from the tables.

## Summary

Data cleaning and processing was the main objective of the project. Messy data was collected from different sources and turned into usable and relevant data through the ETL process mentioned before. The data is now ready to be extracted from the database and used in the hackathon.
