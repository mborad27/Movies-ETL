# ETL, PosgreSQL, and Amazing Prme
## Overview
Amazing Prime is a platform for streaming TV Shows and Movies (the world's largest platform). They would like to develop an algorithm to predict the low budget movies that will become popular so they can buy the streaming rights. Amazing Prime is sponsoring a Hackathon in which they are providing a clean data set of movie data and requesting the participants to predict the popular movies. Britta, a member of the Amazing Prime Video Team, is reponsible to create the datasets for the Hackathon. She requested our help for the datasets. She has two data sources: a piece of Wikipedia for all the movies released ince 1990, and rating data from the Movie Land's website. We assissted Britta into extracting the data from the two sources, transforming it into one clean data set, and loading that data set into an SQL table.

Amazing Prime loved our dataset and would like to keep it updated on a daily basis. Britta would appreciate our help once again to create an automated pipeline that takes in new data, performs relevant transformations, and loads data into existing tables. We will refactor the previous code to create a function that takes the three files (Wikipedia data, Kaggle metadata, and MovieLens rating data) and performs the ETL process by adding the data to a PostgreSQL database.
