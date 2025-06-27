# Netflix-Data-Analysis-Content-Trends-Insights
Analyzed 8,800+ Netflix movies and TV shows to uncover content distribution trends across genres, release years, and countries. Leveraged Python, Pandas, and Matplotlib to perform exploratory data analysis, visualizing key patterns in IMDb ratings and content availability.

Table of Contents¶
Data Decription
1.1 Introduction
1.2 Data source and data set
Load the Packages and Data
Data Profiling
3.1 Understanding the Dataset
3.2 Pre Profiling
3.3 Preprocessing
3.4 Post Profiling
EDA Questions

4.1 What different types of show or movie are uploaded on Netflix?
4.2 What is the Correlation between the features?
4.3 Most watched shows on the Netflix?
4.4 Distribution of Ratings?
4.5 Which has the highest rating Tv show or Movies?
4.6 Finding the best Month for releasing content?
4.7 Highest watched genres on Netflix?
4.8 Released movie over the years?
4.9 movies made on year basis?
4.10 What is the show id and director for 'House of cards'?
4.11 4.11 Show all the movies that were released in year 2000.
4.12 Show only the title of all TV shows that were released in India only.
4.13 Show top 10 director, who gave the highest number of TV shows & Movies to Netflix?
4.14 In how many movies/ tv shows, 'tom Cruise' was cast?
4.15 How many movies got the "TV-14" rating in the caneda?
Conclusions

1. Data Decription:
This Netflix Dataset has information about the TV shows and Movies available on Netflix from the year 2008 to 2021. Netflix is an application that keeps growing exponentially whole around the world and it is the most famous streaming platform.

This dataset collected from Netflix of different TV shows and Movies from the year 2008 to 2021.
show_id: Gives the information about show id.
type: Gives information about 2 different unique values one is TV Show and another is Movie.
title: Gives information about the title of Movie or TV Show.
director: Gives information about the director who directed the Movie or TV Show.
cast: Gives information about the cast who plays role in Movie or TV Show.
country: Gives information about the Name of country.
date_added: Gives information about the tv shows or movie released.
release_year: Gives information about the year when Movie or TV Show was released.
rating: Gives information about the Movie or TV Show are in which category (eg like the movies are only for students, or adults, etc).
duration: Gives information about the duration of Movie or TV Show.
listed_in: Gives information about the genre of Movie or TV Show.
description: Gives information about the description of Movie or TV Show.
1.1. Introduction
This Exploratory Data Analysis is to practice Python skills learned till now on a structured data set including loading, inspecting, wrangling, exploring, and drawing conclusions from data. The notebook has observations with each step in order to explain thoroughly how to approach the data set. Based on the observation some questions also are answered in the notebook for the reference though not all of them are explored in the analysis.

1.2 Data source and data set
This Netflix Dataset has information about the TV shows and Movies available on Netflix from 2018 to 2021. This dataset collected from kaggle website for free.

Dataset link: https://www.kaggle.com/datasets/swatikhedekar/exploratory-data-analysis-on-netflix-data
