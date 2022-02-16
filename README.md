# Movies-ETL

## Project Overview:

Britta with Amazing Prime is preparing for a hackathon. For this project we will be creating an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data. It will then perform the appropriate transformations and loads the data into an existing PostgreSQL database.

For this analysis, we used the following breakdown:
1.	write an ETL function to read three data files,
2.	extract and transform the Wikipedia data,
3.	extract and transform the Kaggle and rating data,
4.	load the data to a PostgreSQL Movie Database.

## Results

### Write an ETL function to read three data files

Deliverable 1 had us take the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.

### Extract and Transform the Wikipedia data

Deliverable 2 had us filter out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.

### Extract and Transform the Kaggle and rating data

Deliverable 3 had us consolidated the redundant data, removed the duplicates, formatted and grouped the data. The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.
### Load the data to a PostgreSQL Movie Database

Deliverable 4 had us load the data to PostgresSQL database and to check to make sure both the movie_data  and the ratings data loaded the information into the databases

![movie_data](https://github.com/backwater-graphics/Movies-ETL/blob/main/Resources/movies_query.png)
![ratings](https://github.com/backwater-graphics/Movies-ETL/blob/main/Resources/ratings_query.png)
---
## Summary:

The ETL function created collects and cleans movie data from different sources (Wikipedia JSON and Kaggle and ratings csv files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.
