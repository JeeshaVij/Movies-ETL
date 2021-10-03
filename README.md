# Overview of the project:

Amazing Prime Video was a platform for streaming movies and TV shows on Amazon Prime. The Amazing Prime Video team would like to develop an
algorithm to predict which low budget movies being released will become popular so that they can buy the streaming rights at a bargain. 
They've decided to sponsor a hackathon. Providing a clean data set of movie data and asking participants to predict the popular pictures. 
There are two data sources: a scrape of Wikipedia for all movies released since 1990, and rating data from the Movie Land's website. The 
data needs to be extracted from two sources, transformed into one clean data set, and finally  be loaded into a SQL table.  

In This project I am creating an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into 
SQL tables. A function is created hat takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the 
ETL process by adding the data to a PostgreSQL database.

 