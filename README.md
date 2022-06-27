#  Module 8: ETL - Extract, Transform, Load

## Overview of the Analysis

### Purpose
To create an automated pipeline that takes in new data, performs appropriate transformations, and loads the data into existing SQL tables. The function will take in three files and perform the ETL process by adding the transformed data into a PostgreSQL database. 

### Resources
* Jupyter Notebook, Python 3.7.13
* Python Libraries: json, pandas, numpy, re, sqlalchemy, psycopg2, time
* pgAdmin, PostgreSQL
* Data Sources: [wikipedia-movie.json](https://github.com/daniel-sh-au/UofT_DataBC_Module08_Movies-ETL/blob/main/Resources/wikipedia-movies.json), [movies_metadata.csv](https://github.com/daniel-sh-au/UofT_DataBC_Module08_Movies-ETL/blob/main/Resources/movies_metadata.csv), ratings.csv

## Deliverable 1: Write an ETL function to read three data files
Code: [ETL_function_test.ipynb](https://github.com/daniel-sh-au/UofT_DataBC_Module08_Movies-ETL/blob/main/ETL_function_test.ipynb)

## Deliverable 2: Extract and Transform the Wikipedia Data
Code: [ETL_clean_wiki_movies.ipynb](https://github.com/daniel-sh-au/UofT_DataBC_Module08_Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)

## Deliverable 3: Extract and Transform the Kaggle Data
Code: [ETL_clean_kaggle_data.ipynb](https://github.com/daniel-sh-au/UofT_DataBC_Module08_Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)

## Deliverable 4: Create the Movie Database
Code: [ETL_create_database.ipynb](https://github.com/daniel-sh-au/UofT_DataBC_Module08_Movies-ETL/blob/main/ETL_create_database.ipynb)

Screenshots: 
| movie_query.png | ratings_query.png |
| --------------- | ----------------- |
| ![movies_query.png](https://github.com/daniel-sh-au/UofT_DataBC_Module08_Movies-ETL/blob/main/Resources/movies_query.png) | ![ratings_query.png](https://github.com/daniel-sh-au/UofT_DataBC_Module08_Movies-ETL/blob/main/Resources/ratings_query.png) |