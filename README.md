# Movies-ETL
Module 8

## **Project Overview**
The Amazing Prime Video company is sponsoring a hackathon to figure out what the best upcoming pieces of media are worth acquiring streaming rights for. In order to get the hackathon started a dataset will be needed of all movies created since 1990 as well as their rating data. This project will be using Python and Pandas to perform data wrangling, PostgreSQL to store the data, and implementing the ETL process to create a system that will automate this data pipeline. 

The steps for the project were as follows:
 - Write an ETL function to read three data files
    - wikipedia-movies.json, movies_data.csv, and ratings.csv
 - Extract and transform the Wikipedia data
    - Since the data included TV shows created since 1990 we made sure to remove those as well as combined any redundant data.
 - Extract and transform the Kaggle data
    - Much like before we made sure to remove the TV shows and combine any duplicate data
 - Create the movie database
    - Once all of our data wrangling was complete it was time to get it ready for the hackathon. The filtered and transformed information was pushed into our PostgreSQL database

## Summary
The process for Extracting, Transforming, and Loading data is standard in the industry in order to create complete pictures with the information gathered. We can see here that it can even be accomplished with different sources and that it can also be automated for future ease. 