# Movies - ETL Process
## Deliverable 1: ETL_function_test.ipynb
Created a function that reads in the three data files (ratings csv, movies csv, wiki movies json) and creates three separate DataFrames.
## Deliverable 2: ETL_clean_wiki_movies.ipynb
Extracted and transformed the Wikipedia data to merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, used a try-except block to catch errors.
## Deliverable 3: ETL_clean_kaggle_data.ipynb
Extracted and transformed the Kaggle metadata and MovieLens rating data, then converted the transformed data into separate DataFrames. Merged the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Merged the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.
## Deliverable 4: ETL_create_database.ipynb
Added the movies_df DataFrame and MovieLens rating CSV data to a SQL database.

