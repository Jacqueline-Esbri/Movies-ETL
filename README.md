# Movies-ETL

## Analysis Overview

The purpose of this analysis was to learn the process to create data pipelines, also known as Extract, Transform, Load (ETL). This process, which is often the first step before performing any analysis, consists of moving robust data around between databases. ETL ensures that the data is consistent and maintains its integrity. The main goal of the assignment was to create  an algorithm for a mock company called Amazing Prime; a platform for streaming movies and TV shows. The algorithm will enable its team to predict which low budget movies being released would become popular in order to purchase at a low price. 

During this exercise, we created ETL pipelines from raw data to a SQL database. Data was also extracted from different sources using python, and cleaned and transformed using Pandas. The last step was to ensure the data was transformed into a consistent structure and then loaded to a data target. PostgreSQL, a relational database, was use for this purpose.

The iterative process for cleaning the data was broken down as follows:

- Inspecting the data
- Identifying problems with the data
- Making a plan and deciding if it was worth the time to fix it
- Executing the data



## Resources

- Python and Pandas
- PostgreSQL and pgAdmin
- Three CSV files  
1. Movies_metadata.csv
2. Wikipedia-movies.JSON
3. Ratings.csv