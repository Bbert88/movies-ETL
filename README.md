# Analysis of Movie Data Following the Extract, Transform, Load Method Using Python, SQLAlchemy, and PostgreSQL

## Overview

This project involved extracting movie data from three different sources (two csv files, one json web scrape), cleaning the data, and then loading it in to a database. The extraction involved reading the data from each source and storing the data using the Python Pandas library. All data was then stored in 3 separate DataFrames. Each DataFrame was then transformed by a rigorous cleaning and re-structuring process. This involved creating multiple functions, formatting columns, and deleting obsolete columns in each DataFrame to achieve a desired and easy to read DataFrame. The cleaned DataFrames were then merged and the resulting DataFrames were then reviewed and cleaned again. Once the transformation of the data was complete, the data was then loaded in to a relational database (PostgreSQL). Screenshots of two simple SQL queries were taken to show the vast number of rows each Table included: [Query Screenshots](https://github.com/Bbert88/movies-ETL/tree/main/Resources). Please reference the ETL files for the code which was written to accomplish this task.

## Resources

- Data Sources: Wikipedia web scrape of movie data in JSON format & Two csv files from [Kaggle](https://www.kaggle.com/) with movie data/ratings.
- Software: Jupyter Notebook, PostgreSQL/PgAdmin, Visual Studio Code 1.38.1
- Language: Python
