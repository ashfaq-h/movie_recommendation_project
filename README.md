# The-Movie-Recommender

![Python](https://img.shields.io/badge/Python-3.8-blueviolet)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie. 

The data for the project was extracted from IMDB dataset from Kaggle, Wikipedia portals and TMDB API employing csv extraction, **web scraping** and **beautifulsoup4**. The sentiments of the reviews of the movies were analyzed using **TF-IDF vectorizer** and **Naïve Bayes classifier** for which the accuracy of the model was optimized for **98.7%**. The feature extraction was done with **CountVectorizer** and after which the similarity is calculated using **Cosine Similarity**.

This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `beautifulsoup4` and performed sentiment analysis on those reviews.

### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)
