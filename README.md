# Coding-Raja-Technologies-Internship
# Movie Recommendation System

This repository contains code for building a movie recommendation system using collaborative filtering techniques. The system suggests movies to users based on their preferences.

## Overview

The recommendation system is built using Python and utilizes the Surprise library for collaborative filtering algorithms. It includes the following components:

1. Data Collection: Movie ratings data is collected from users, including movie IDs, user IDs, and ratings. The MovieLens dataset is used for this purpose.
2. Data Preprocessing: The collected data is cleaned, missing values are handled, and exploratory data analysis is performed.
3. User-Item Matrix: A user-item matrix is created where rows represent users, columns represent movies, and entries represent ratings.
4. Collaborative Filtering: Collaborative filtering algorithms such as Singular Value Decomposition (SVD) are implemented using Surprise library.
5. Model Evaluation: The recommendation system's accuracy is evaluated using metrics like Root Mean Squared Error (RMSE).
6. Top-N Recommendations: Top-N movie recommendations are generated for a specific user based on their preferences.
7. Interactive Interface: A simple Flask web interface is created to allow users to input their preferences and receive movie recommendations.

## Installation

1. Clone the repository:


2. Install dependencies:


2. Install dependencies:


## Usage

1. Run the Flask web interface:


2. Access the web interface in your browser at `http://localhost:5000/recommendations?user_id=<user_id>` where `<user_id>` is the ID of the user for whom you want to get recommendations.

## Repository Structure

- `app.py`: Flask web application for the interactive interface.
- `recommendation_system.py`: Code for building the recommendation system.
- `README.md`: This file providing an overview of the project and instructions for usage.
- `requirements.txt`: List of Python dependencies.

## Credits

- MovieLens dataset: GroupLens Research (https://grouplens.org/datasets/movielens/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
