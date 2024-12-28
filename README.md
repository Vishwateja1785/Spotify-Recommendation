# Spotify Songs Recommender System

This project analyzes Spotify song features and develops a recommendation system based on song characteristics.

## Project Overview

This project focuses on analyzing Spotify data to gain insights into music trends, predict song popularity, and create a recommendation system. The analysis covers various aspects including exploratory data analysis, feature engineering, predictive modeling, and content-based recommendation systems.

## Dataset
The project utilizes the Spotify 160k dataset, which contains over 160,000 songs with 18 features including:
- **Sound-related features**: loudness, tempo, acoustics, valence, etc.
- **Metadata**: artist information, release dates
- Songs spanning from 1921 to 2021

## Features

- **Data Analysis**: Explores Spotify's song database, focusing on key audio features.
- **Feature Engineering**: Processes and transforms raw data into meaningful insights.
- **Recommendation Algorithm**: Implements a system to suggest songs based on audio characteristics (Manhattan Distance-based recommender, Cosine Similarity-based recommender).
- **Visualization**: Presents data insights through graphs and charts for better understanding.

## Key Findings

- Artist collaborations tend to be more popular
- Acoustic songs have reduced over the years
- High energy songs with electric or electronic instruments have a better chance of popularity

## Future Work

- Incorporate more recent artist ranking data to improve predictions
- Explore hybrid recommendation systems combining collaborative and content-based filtering
- Implement natural language processing to analyze recent music trends

## Technologies Used

- Python
- Pandas for data manipulation
- Scikit-learn for machine learning algorithms
- Matplotlib, Seaborn and Tableau for data visualization
