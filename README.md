Hybrid Recommender System - MovieLens

A recommendation system is a technique for filtering information that determines the degree of evaluation that a user will give to a particular item.

The following types of recommender systems are very popular:

Association Rule Learning

Content Based Recommendation

Collaborative Filtering

User-based

Item-based

Model-based (Matrix Factorization)

In this study, I made a movie recommendation using both item-based and user-based recommender methods.

Business problem:

Suggesting 10 movies for users using item-based and user-based recommender methods.

Dataset Story:

The dataset was provided by MovieLens, a movie recommendation service. It contains movies and their rating scores. There are 2,000,0263 ratings on 27,278 movies in the dataset. This data set was created on October 17, 2016. Includes 138,493 users and data from 09 January 1995 to 31 March 2015. Users are randomly selected. It is known that all selected users voted for at least 20 movies.

movie.csv

movieId: Unique movie number.

title: Movie name

genres: Genre

rating.csv

userid: Unique user number. (UniqueID)

movieId: Unique movie number. (UniqueID)

rating: The rating given to the movie by the user

timestamp: Date of evaluation
