# Movies-ETL
Module 8

### Overview of Analysis
For this analysis, I created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I used one function that takes in three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

### Process

  1. Write an ETL Function to Read Three Data Files
  2. Extract and Transform the Wikipedia Data
  3. Extract and Transform the Kaggle Data
  4. Create the Movie Database with two tables

### Results
Using Python, I cleaned, merged datasets, and exported two new tables into PostgresSQL. 

**Write an ETL Function to Read Three Data Files**

      1. File 1: wiki_movies_df
      Image HERE
      
      2. File 2: kaggle_metadata
      Image HERE
      
      
      3. File 3: ratings
      Image HERE


**Extract and Transform Wikipedia and Kaggle Data**
Extract & Transform Wikipedia Data Image Here
3 images


 **Create the Movie Database with two tables**
 
 Extract & Transform Kaggle Data Image Here
 1 or 2 images Here
 
 
  **Create the Movie Database with two tables**

at least 2 images here
 
 ### Summary

Three files were extracted:
  1. Wikipedia (json)
  2. Kaggle Movie 
  3. Kaggle Ratings
  
Then I transformed and merged them. Both the movie and rating files were loaded into a PostSQLA movies and ratings file were loaded into a PostgreSQL database that can be easily accessed.

