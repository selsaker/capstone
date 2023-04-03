## Capstone 

## Overview
Dataset from GHO was utilized to extract the correlation between our target variable life expectancy and dependant variables 'Schooling' and 'Alcohol.'

We are trying to predict the target life expectancy through these two dependant variables.


## About this Dataset
- The data is sourced from The Global Health Observatory (GHO) data repository under World Health Organization.
This data is from the time period of 2000 to 2015.
- In a nutshell, this data consists of immunization factors, mortality factors, economic factors, social factors and other health related factors.
- Due to time constraints, this dataset is already prepopulated and found online.
- Features include life expectancy, infant deaths, BMI index, population, HIV/AIDS, schooling, and much more.


### What packages did we use?
 - Matplotlib
 - Pandas
 - SQL (SQLITE3)
 - Numpy
 - Seaborn
 - Scipy.Stats
 - 
 
 ## Business Understanding
### Current Situation 
The movie business has been growing fast during the last decade and with the appearance of streaming services, movies are becoming reachable to everybody. The competition is tough so only a few new movie studios succeed. 
### What can we do?
We can find out a simple formula to make a great movie!
### How are we doing it?
We have researched on different movie databases (that will be discussed in detail later), analyzed important metrics and found patterns with the help of statistics. 
As a data-driven team, we take decisions based on facts and we want to share this philosophy with CV. 

## Data Understanding Analysis 
The source of the data has come from many different areas. These different datasets include:
 - Box Office Moji
 - IMDB
 - Rotten Tomatoes
 - The Movie DB
 - The Numbers

The data from the sources is very succinct and valuable.  There are many possibilities and comparisons that can be done. Just a few categories include directors, producers, reviews, genres,  ratings, studios, theatre date, revenue, etc.

When one thinks of a movie the first thoughts that populate are who is being cast, who is putting it together, and what is the overarching theme?  To find the answer to these questions we will explore the data. 

### Who should be cast?
To understand who should be put in front of the camera it is important to look at popularity. To get a predictor of popularity our data scientists will analyze which actors have the most reviews. Out of the actors and actresses with the greatest number of reviews, we will order them to depict the top to least favorites by their average rating overall.

### Who should put it together?
To get an idea of who should be directing this movie, it is also necessary to look at popularity and reviews as well.  One way to see how favored a director is by looking at the Rotten Tomatoes dataset, specifically the fresh or rotton  data. This data is binary either yes, they are favored hence "fresh" or no they are not favored hence "rotten." Looking at the ratio of fresh to rotten can give us great insight on which director is highly favored. 

### What is the overarching theme?
Lastly, much of the time spent was researching which genre should the company invest in. The team wanted to find a genre that is highly favored, but not already oversaturated in the market. This again was looking at popularity of genres by counting all the movies that fall under each genre; as well as looking at the overall ratings of the movies in each genre.


## Statistical Communication 
