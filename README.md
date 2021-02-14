# Movies-ETL

## Overview
Generating a dataset for movies from differing sources (wikipedia and kaggle). After reading in this data we want to utilize the ETL process to clean, combine, and save this data to a database. For this analysis there are four main deliverables:

 - ETL_function_test.ipynb
 - ETL_clean_wiki_movies.ipynb
 - ETL_clean_kaggle_data.ipynb
 - ETL_create_database.ipynb


## Summary
These deliverables are eseentialy building one ultimate ETL process found int he ETL_create_database file. Using Python Pandas library we created a function to clean the datasets (ETL_function_test). Using this function we clean both the wiki and kaggle data (ETL_clean_wiki_movies and ETL_clean_kaggle_data). Finally, we load these results to a database (ETL_create_database).