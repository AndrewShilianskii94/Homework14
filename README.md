# Homework14
Movie Catalog API
This is a simple Flask-based API that provides information about movies stored in a SQLite database. The API allows you to retrieve a list of movies and filter them by genre.

Prerequisites
Python 3.x
Flask
SQLite3
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/movie-catalog-api.git
Navigate to the project directory:

bash
Copy code
cd movie-catalog-api
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Make sure you have the SQLite database file (netflix.db) in the project directory.

Start the API server:

bash
Copy code
python main.py
The API server should now be running on http://localhost:5000.

API Endpoints
GET /api/movies: Retrieve a list of all movies.
GET /api/movies/genre/<genre>: Retrieve a list of movies filtered by genre.
Example Requests
Retrieve all movies:

bash
Copy code
GET /api/movies
Retrieve movies of a specific genre (e.g., Comedy):

bash
Copy code
GET /api/movies/genre/Comedy
Response Format
The API returns data in JSON format. Each movie object has the following attributes:

title: The title of the movie.
country: The country where the movie was produced.
release_year: The year when the movie was released.
genre: The genre of the movie.
description: A brief description of the movie.
Contributing
Contributions are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Enjoy using the Movie Catalog API!
