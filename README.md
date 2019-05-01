# Predicting IMDB Ratings

Today’s movie watcher is spoilt for choice with increase in movie streaming platforms, DVD rental services and easy access to movie theatres. Knowing a movie’s rating before watching the movie helps reduce the decision fatigue arising out of increased options. IMDb (Internet Movie database) is often a go-to source for knowing a movie’s ratings, user reviews, plot, casting and other details before watching that movie. The ratings in IMDb are a function of the ratings given by the users.

But unfortunately, IMDb allows users to provide ratings and reviews only after movie release. So, if you want to select a movie for a first day show, you don’t have the ratings to rely on.

## Objective: 
To develop a model to predict IMDB rating on a scale of 1 to 10 for an upcoming movie

## Dataset used

The dataset to be used in the project has been acquired from IMDB website from the link: https://www.imdb.com/interfaces/.
IMDB has 6 relevant datasets contained in separate gzipped, tab-separated-values (TSV) formatted files. These datasets have details of all the movies, tv episodes, documentaries etc for all countries of the world.

## Tools used: 

Python, Multiple regression techniques -  Linear Regression
Regularization Models-Ridge, Lasso 
Ensemble Models-Random Forest, Gradient Boost, Ada Boost
Stack model - Linear, Random Forest, Gradient Boost

## Detailed Process
To understand the whole process these links can be followed in order:

[Data Wrangling](https://github.com/koshika15/Project-1-Predict-IMDB-rating-of-upcoming-movies/blob/master/B.%20Data_wrangling.ipynb)

[Data Story](https://github.com/koshika15/Project-1-Predict-IMDB-rating-of-upcoming-movies/blob/master/C.%20Data_Story.ipynb)

[Statistical Inference](https://github.com/koshika15/Project-1-Predict-IMDB-rating-of-upcoming-movies/blob/master/D.%20EDA.ipynb)

[Machine Learning](https://github.com/koshika15/Project-1-Predict-IMDB-rating-of-upcoming-movies/blob/master/E.%20Machine%20Learning.ipynb)

## Project Report
Click [here](https://github.com/koshika15/Project-1-Predict-IMDB-rating-of-upcoming-movies/blob/master/Capstone%20Project%201_%20Final%20Report.pdf) for the full project report.

## Result
The objective of this project was to predict the IMDB rating of movies before they are released. The model we came up with gives us good results for movies rated between 4 and 8, most of them within ± 1 error. For the extreme ratings, as the data points are not enough, the model gives error within ±2 error points.
