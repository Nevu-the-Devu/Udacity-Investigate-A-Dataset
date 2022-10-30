# Udacity-Investigate-A-Dataset

# Project: TMDB Movies Data Analysis

## By Ijoma Chidimma

## Introduction

### Dataset Description 

>The Movie Database (TMDB) is a data set which includes the records of 10,000 movies that have been releases over a 56 year period and various attributes of said movies.

>**Column names**:  

>`id` - identification number 
`imdb_id` - unique movie identification code  
`popularity`  - popularity ratings in numeric value  
`budget` - amount spent in dollars  
`revenue` - amount generated from movie in dollars  
`original_title` - name of movie  
`cast` - name of main actors  
`homepage` - webpage of movie  
`director` - director of movie     
`tagline` - unique to each movie  
`overview` - brief description of movie  
`runtime` - total time the movie runs in numeric value  
`genres` - genre of movie  
`production_companies` - list(s) of companies who produced movie  
`release_date` - date movie was released in date format  
`vote_count`  - total vote counts in numeric format  
`vote_average` - average vote in numeric format  
`release_year` - year movie was released  
`budget_adj` - budget of the associated movie
in terms of 2010 dollars, accounting for inflation over
time.  
`revenue_adj` - revenue of the associated movie
in terms of 2010 dollars, accounting for inflation over
time. 

### Inspiration behind Analysis
>Hollywood has been a pivotal industry for decades. Not only do they supply billions of people around with entertainmenth that has shaped generations and influenced pop culture, but they make billions of dollars while doing it. Their productivity has been something I have admired and I must confess i am an avid moive goer myself. So when Udacity presented the opportunity to analyze some data based on Hollywood movies for a project, i took the opportunity immediately. Odds are this is nor real world data but if it is then some of the things i found out are definitely insights Hollywood analysts used for descriptive and prescriptive analysis.



### Question(s) for Analysis
1. Which movie titles had the highest revenue?
2. Which movie titles had the highest profit? 
3. Which companies have made the highest total profit from movies of all time?
4. Which companies have spent the highest total budget from movies of all time?
5. Which movies are the most popular of all time?
6. Which directors are most sought after to make movies?
7. Are these same directors ususally associated with more popular movies?
8. What is the trend in movie popularity over the years?
9. Is there a correlation between vote_count and profit?
10. What kinds of properties are associated with the more profitable movies?
11. Given the budget of movies at when it was made and its values as at 2010, is the economy getting better or worse for the movie industry? Is it affecting the profit made by movies compared to their value as at 2010?


### Conclusions
1. Avatar, Star Wars: The Force Awakens and Titanic were the movies that have generated the highest revenue.
2. Avatar, Star Wars: The Force Awakens and Titanic were the movies that generated the most profit.
3. Paramount Pictures, Universal Pictures and Warner Bros. were the production companies that have generated the most profit from their movies
4. Warener Bros. Universal Pictures and Paramount Pictures were the production companies that have spent the most budget for their movies
5. Jurassic World is the most popular movie of all time
6. Woody Allen, Clint eastwood and Steven Speilberg are the directors most sought after and have directed the most movies
7. The most sought after directors are not usually responsible for popular movies as the most actually popular directors have quite few movies compared to those most sought after. These directors include Colin Trevorrow, David Leitch and Chad Stahelski
8. Movies seem to be getting more popular and higher pupularity ratings as time moves on
9. Profitability of movies is quite complex as it is affected by a lot of factors at once. The strongest factor seems to be revenue however further analysis will need to be done to determine why and determine the factors revenue is affected by.
10. Although little to no correlation exists between them, high profit movies usually have higher vote counts, budgets and popularity ratings.
11. The economy seems to be getting worse as inflation affects the value of the U.S. dollar. However, this seems to have little to no effect on the movie industry as the value of profits generated and budgets spents appear to adapt based on th current economy.


### Limitations
1. Ironman 3 has some of the highest revenues but not the highest profits
2. The Net has some of the highest profits but not the highest revenues
3. Marvel Studios and Lucasfilms are some of the biggest spenders budget-wise but don't generate some of the highest profits
4. Touchstone Pictures and Columbia Pictures Corperation are some of the biggest profiters but aren't some of the biggest spenders
5. Very large appearance of zero values in the `budget` and `revenue` columns
