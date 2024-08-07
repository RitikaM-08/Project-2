# Project-2
Project: Movie Database Analysis
This project involves creating and analyzing a movie database using MySQL. The database includes tables for movies, actors, directors, genres, and user ratings. The aim is to use complex SQL queries to extract meaningful insights from the data.

## Database Schema

The database schema consists of the following tables:

- `actors`: Contains actor information.
- `directors`: Contains director information.
- `genres`: Contains genre information.
- `movies`: Contains movie information.
- `movie_genres`: Many-to-many relationship table linking movies and genres.
- `movie_actors`: Many-to-many relationship table linking movies and actors.
- `user_ratings`: Contains user ratings for movies.

## Data Insertion

Sample data is inserted into the tables to facilitate analysis. This includes:
- Actors: Leonardo DiCaprio, Johnny Depp, Scarlett Johansson.
- Directors: Christopher Nolan, Steven Spielberg.
- Genres: Action, Drama, Sci-Fi.
- Movies: Inception, Titanic.
- User Ratings: Ratings for the above movies.

## Queries

The project includes complex queries to analyze the data:

1. **Movies Released After 2000 with High Ratings**: Finds all movies released after 2000 with an average user rating of 4 or higher.
2. **Actors in Multiple Movies**: Lists all actors who have acted in more than one movie.
3. **Top Directors by Average Ratings**: Finds the top 3 directors with the highest average movie ratings.
4. **Most Popular Genre**: Gets the genre with the most movies.
5. **Movies with Multiple Genres**: Lists movies with multiple genres along with their genres.
