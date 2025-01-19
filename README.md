# Netflix Movies and TV shows Data analysis using SQL

![Netflix Logo](https://github.com/snehakr54/Netflix_sql_project/blob/main/Netflix.jpg)

## Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows data using SQL. The goal is to extract valuable insight and 
answer various business questions based on the datasets. The following README provides a detailed account of project objectives, Business 
problems, solutions, findings and conclusions.
## Objective
* Analyze the distribution of content types (Movies vs TV shows).
* Identify the most common rating for Movies and TV shows.
* List and analyze content based on release years, countries and durations.
* Explore and categorize content based on specific criteria and keywords.
## Dataset
The data for this project is sourced from the Kaggle dataset:
    Dataset link: https://github.com/snehakr54/Netflix_sql_project/blob/main/Netflix_data.zip

##Schema
***sql
DROP TABLE IF EXITS netflix;
CREATE table netflix
(
  show_id VARCHAR (6),
  type	VARCHAR (10),
  title   VARCHAR (150),
  director VARCHAR (208),
  casts VARCHAR (1000),
  country	VARCHAR (150),
  date_added VARCHAR (50),
  release_year INT,
  rating	 VARCHAR (10),
  duration VARCHAR (15),
  listed_in	VARCHAR (150),
  description VARCHAR (250)
);
...





   
  
