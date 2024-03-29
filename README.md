# Movies-ETL
Module 8

### Overview of Analysis
For this analysis, I created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I used one function that takes in three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

### Process

 - Deliverable 1: Write an ETL Function to Read Three Data Files
 - Deliverable 2: Extract and Transform the Wikipedia Data
 - Deliverable 3: Extract and Transform the Kaggle Data
 - Deliverable 4: Create the Movie Database with two tables

### Results
Using Python, I cleaned, merged datasets, and exported two new tables into PostgresSQL. 

**Write an ETL Function to Read Three Data Files**

      1. File 1: wiki_movies_df
![](https://github.com/nadiezhdamhb/Movies-ETL/blob/main/Resources/wiki_movies_df.png)
      
      2. File 2: kaggle_metadata
![](https://github.com/nadiezhdamhb/Movies-ETL/blob/main/Resources/kaggle_metadata.png)
      
      
      3. File 3: ratings
![](https://github.com/nadiezhdamhb/Movies-ETL/blob/main/Resources/ratings_image.png)


**Extract and Transform Wikipedia, Kaggle, and rating data**


Extract & Transform Wikipedia Data Image Here
![](https://github.com/nadiezhdamhb/Movies-ETL/blob/main/Resources/clean_wiki_movies_image.png)



![](https://github.com/nadiezhdamhb/Movies-ETL/blob/main/Resources/wiki_movies_list.png)


 
 Extract & Transform Kaggle Data Image Here
 ![](https://github.com/nadiezhdamhb/Movies-ETL/blob/main/Resources/movies_df.png)
 
 
 
  
 Extract & Transform rating Data Image Here
 ![](https://github.com/nadiezhdamhb/Movies-ETL/blob/main/Resources/movies_with_ratings.png)
 
 
  **Create the Movie Database with two tables**

![](https://github.com/nadiezhdamhb/Movies-ETL/blob/main/Resources/movies_query.png)



![](https://github.com/nadiezhdamhb/Movies-ETL/blob/main/Resources/ratings_query.png)


 ### Summary

Three files were extracted:
  1. Wikipedia (json)
  2. Kaggle Movies_metadata
  3. Kaggle Ratings
  
Then I transformed and merged them. Both the movies and rating files were loaded into a PostSQLA movies and ratings file were loaded into a PostgreSQL database that can be easily accessed.

