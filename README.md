# Movies-ETL
The goal of this project was to extract, transform and load (perform an ETL) a data set of movie data and movie ratings (from Kaggle and Wiki) to be used to evaluate the success of movies. Success of a movie comes from the trends identified in the data sets such as ratings, genre, budget ect.  

## Overview
The code used in this project was created in Jupyter Notebook to clean and transform the data from the collected source. The code uses Pandas and regrex expressions to find any patterns. 

Project Checkpoints-
* Deliverable 1: Write an ETL Function to Read Three Data File
* Deliverable 2: Extract and Transform the Wikipedia Data
* Deliverable 3: Extract and Transform the Kaggle data
* Deliverable 4: Create the Movie Database


## ETL

The data was taken from their respectful sources and added to the code in Jupyter Notebook to be loaded into the code. After the extraction comes the transform which included writing the columns into a new DataFrame to make them easier to use (transforming them from raw data to cleaned, usable data).  Then for the Load piece, we moved the new created data set into PostgreSQL database for further quires. Because the combines data set contained over 26 million enteries, the import was broken up into 3 parts to ease load execution. And once the DataFrame was imported the readablility using SQL quieres were successfully easy. 
The pic below is the ratings determined by the new DataFrame created

<img width="450" alt="movies_query" src="https://user-images.githubusercontent.com/86068655/173499114-30c01bcc-b647-4af1-9581-68319f337abc.png">

The pic bewlo is the total movies in the created movie DataFrame

<img width="450" alt="ratings_query" src="https://user-images.githubusercontent.com/86068655/173499126-dc0da12c-4d18-436e-aecb-19e5ea5fa1a1.png">


## Summary 
This project shows the systematic approach to ETL and how to manage data from different sources. This project gave a clear methodology to gathering data info a workable form to easily manipulate and analyze to find a certain result.  
