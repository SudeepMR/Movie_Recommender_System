# Movie_Recommender_System

## Context:
Over the past two decades, there has been a monumental shift in how people access and consume video content. With the universal access to broadband internet, numerous platforms like YouTube, Netflix, and HBO Go emerged and steadily grew to prominence.
Although not a household name in itself, OTT is the exact technology that made the streaming revolution possible.
OTT stands for “Over The Top” which refers to any video streaming service delivering content to the users over the internet, however, there are subscription charges associated with the usage of such platforms such as PrimeVideo, Netflix, HotStart, Zee5, SonyLiv, etc.
But choosing your next movie to watch can still be a daunting task, even if you have access to all the platforms.

## Objective:
1. Create a popularity-based recommender system at a genre level. The user will input a genre (g), minimum rating threshold (t) for a movie, and no. of recommendations(N) for which it should be recommended top N movies which are most popular within that genre (g) ordered by ratings in descending order where each movie has at least (t) reviews.

     #### Example:
     Input: 
     + Genre (g) : Comedy
     + Minimum reviews threshold (t): 100
     + Num recommendations (N) : 5

2. Create a content-based recommender system that recommends top N movies based on similar movie(m) genres.

     #### Example:
     Input:
     + Movie Title (t): Toy Story
     + Num recommendations (N): 5

3. Create a collaborative based recommender system which recommends top N movies based on “K” similar users for a target user “u”

     #### Example:
     Input:
     + UserID: 1 
     + Num recommendations(N): 5
     + Threshold for similar users (k: 100

## About the Data:
There are two data files which are provided:

#### Movies.csv
+ movieId: ID assigned to a movie
+ title: Title of a movie
+ genres: pipe-separated list of movie genres.

#### Ratings.csv
+ userId: ID assigned to a user
+ movieId: ID assigned to a movie
+ rating: rating by a user to a movie
+ Timestamp: time at which the rating was provided.

## Steps and Tasks to be performed:
+ Import libraries and load dataset
+ Exploratory Data Analysis including:
   + Understanding of distribution of the features available
   + Finding unique users and movies
   + Average rating and Total movies at genre level.
   + Unique genres considered.
+ Design the 3 different types of recommendation modules as mentioned in the objectives.
+ Additional/Optional: Create a GUI interface using Python libraries (ipywidgets etc.) to play around with the recommendation modules.
