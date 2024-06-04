# Movie Recommender System

Welcome to the Movie Recommender System! This application, built using Streamlit, provides personalized movie recommendations based on user preferences.

## Demo

![Movies Recommender System](https://github.com/himanshu-banodha/movie-recommender-system/blob/main/image/movie-recommender-system.png)

## What is a Recommender System?

A recommender system is a type of information filtering system that seeks to predict the rating or preference a user would give to an item. These systems are widely used in various domains such as movies, music, news, books, research articles, search queries, social tags, and products in general.

### Types of Recommender Systems

1. **Content-Based Filtering**: This approach recommends items similar to those that a user has liked in the past. It uses item features and user preferences to make recommendations. For example, if a user likes movies with certain actors or genres, the system will recommend similar movies.

2. **Collaborative Filtering**: This method makes recommendations based on the preferences of other users. It assumes that if user A has a similar interest to user B, then items liked by user A might also interest user B. Collaborative filtering can be:
   - **User-Based**: Recommendations are made based on similar users' preferences.
   - **Item-Based**: Recommendations are made based on the similarity between items.

3. **Hybrid Methods**: These combine both content-based and collaborative filtering approaches to improve recommendation accuracy. By leveraging the strengths of both methods, hybrid systems can mitigate the weaknesses of each individual approach.

## About This Project

This movie recommender system is built using **Streamlit**, **CountVectorizer**, and **Cosine Similarity**. Here's a brief overview of how these components work together:

- **Streamlit**: A fast way to build and share data apps. It allows us to create a web application for our recommender system with an intuitive and interactive user interface.
- **CountVectorizer**: This is used to convert a collection of text documents to a matrix of token counts. In our case, it transforms the movie descriptions (tags) into a vector format suitable for the recommendation algorithm.
- **Cosine Similarity**: This metric measures the cosine of the angle between two non-zero vectors in a multi-dimensional space. It helps in calculating the similarity between the movies based on their vector representation, which is crucial for providing accurate recommendations.

## Features

- **Personalized Recommendations**: Get movie suggestions tailored to your tastes.
- **Search Movies**: Look up information about any movie.
- **User-Friendly Interface**: Easy-to-navigate UI with a clean design.


## Dataset

The movie data used in this application is sourced from [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).


## Usage

1. Open your web browser and go to `http://localhost:8501`.
2. Enter your movie preferences or search for a specific movie.
3. Get your personalized movie recommendations!


Happy movie watching!

---
