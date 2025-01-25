# Task_1_0

Task-1
Movie Recommendation System
Overview
This Python project allows users to explore and recommend movies based on genres, ratings, or popularity using a movie dataset. Users can filter movies, search by title or keywords, add reviews, and generate recommendations.

Features
Load and Explore Dataset:

Load the dataset from a CSV file.
View an overview, structure, and statistics of the dataset.
Filter Movies:

Filter movies by genre, release year, or director.
Search Movies:

Search for movies by title or keywords in the description or genre.
Add Ratings and Reviews:

Add user ratings and reviews for movies.
Update the average rating and user review fields.
Top 10 Lists:

Generate "Top 10" movie lists by genre, release year, or overall ratings.
Data Visualization:

Visualize rating distributions.
Display the top 10 most common movie genres.
Interactive Menu:

Access all features through an interactive, text-based menu.
Requirements
Python 3.x
Pandas
Matplotlib
How to Use
Set Up the Environment:

Install the required libraries:
pip install pandas matplotlib
Upload the dataset (7_Movie_Recommendation_System.csv) to your working directory or Google Colab environment.
Run the Script:

Load the Python script in your preferred IDE or Google Colab.
Update the file_path variable with the dataset path.
Explore and Interact:

Use the interactive menu to perform actions like filtering, searching, and adding reviews.
Dataset Format
The CSV file should include the following fields:

Movie ID: Unique identifier for each movie.
Title: Movie title.
Genre: Movie genre(s).
Release Year: Year of release.
Rating: Average user rating.
Number of Votes: Total number of ratings.
Duration: Movie duration in minutes.
Director: Director's name.
Example Usage
1. Load Dataset
movies_df = load_dataset('7_Movie_Recommendation_System.csv')
explore_dataset(movies_df)
2. Filter Movies
filtered_movies = filter_movies(movies_df, genre='Action', year=2020)
display(filtered_movies)
3. Add Ratings and Reviews
movies_df = add_user_feedback(movies_df, movie_id=1, user_rating=4.5, user_review='Amazing movie!')
4. Visualize Data
visualize_data(movies_df)
License
This project is open-source and available for personal or educational use.