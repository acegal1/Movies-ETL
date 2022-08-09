# Movies-ETL

# Extract, Transform, Load

## Purpose

1. Create an ETL pipeline from raw data to a SQL database.
2. Extract data from disparate sources using Python.
3. Clean and transform data using Pandas.
4. Use regular expressions (Regex) to parse data and to transform text into numbers.
5. Load data with PostgreSQL and verify in PgAdmin.

The project included extracting a large data set from Kaggle, then transforming the data into a usable dataset for a "hacking competition." Once the data was transformed and narrowed in scope for the hack-a-thon, the DataFrames were loaded into PostgresSQL.

# Results

## Deliverable 1 : Write an ETL Function to Read Three Data Files

Wikipedia Movies JSON file, starting with 193 Columns:

![Wikipedia_Movies](https://github.com/acegal1/Movies-ETL/blob/main/images/Wikipedia_Movies.png)

Kaggle Movie Metadata, 24 columns

![Kaggle_Moive](https://github.com/acegal1/Movies-ETL/blob/main/images/Kaggle_Moive.png)

Kaggle Ratings data, 2602489 rows by 4 columns

![Ratings](https://github.com/acegal1/Movies-ETL/blob/main/images/Ratings.png)

## Deliverable 2: Extract and Transform the Wikipedia Data

Wikipedia Movies transformed, 23 columns

![dev2_wiki_t](https://github.com/acegal1/Movies-ETL/blob/main/images/dev2_wiki_t.png)

Wikipedia Movies, making the column names more succinct and uniform, 7033 rows of data.

![dev2_wiki_t](https://github.com/acegal1/Movies-ETL/blob/main/images/dev2_columns.png)

## Deliverable 3: Extract and Transform the Kaggle data

movies_with_ratings_df DataFrame 41 columns

![dev3_41](https://github.com/acegal1/Movies-ETL/blob/main/images/dev3_41.png)

Movie dataFrame 31 columns

![dev3_31](https://github.com/acegal1/Movies-ETL/blob/main/images/dev3_31.png)


## Deliverable 4: Create the Movie Database

Creating the Movie Database

![dev4_db](https://github.com/acegal1/Movies-ETL/blob/main/images/dev4_db.png)

Verifying the data in PgAdmin

Movies Query

![dev4_movies](https://github.com/acegal1/Movies-ETL/blob/main/images/dev4_movies.png)

Ratings Query

![dev4_ratings](https://github.com/acegal1/Movies-ETL/blob/main/images/dev4_ratings.png)


# Summary

The ETL function created collects and cleans movie data from different sources (Wikipedia JSON and Kaggle and ratings csv files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.