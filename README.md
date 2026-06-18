# 🎬 Movie Recommendation System

## Overview

This project recommends movies similar to a selected movie using a content-based recommendation approach. The system analyzes movie genres, keywords, cast members, crew, and overviews to find movies with similar characteristics.

## Features

- Content-Based Filtering
- NLP Text Processing
- Cosine Similarity Matching
- Fast Movie Recommendations
- TMDB Movie Dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- CountVectorizer
- Cosine Similarity

## How It Works

1. Merge movie and credits datasets.
2. Extract important features such as genres, keywords, cast, crew, and overview.
3. Create tags for each movie.
4. Convert text data into numerical vectors using CountVectorizer.
5. Compute cosine similarity between movies.
6. Recommend the most similar movies to the user.

## Example

Input:

Avatar

Recommended Movies:

- Guardians of the Galaxy
- John Carter
- Star Trek
- Interstellar
- Titanic
