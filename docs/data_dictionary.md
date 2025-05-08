# Data Dictionary
| Field Name      | Data Type          | Description                   |
|-----------------|-------------------------------- |----------------------------|
| `title`       | String             | Title of the book and its movie adaptation (standardized for merge). |
| `imdb_id`   | String                 | Unique identifier for the movie on IMDb.|
| `release_year_movie` | Integer        | Release year of the movie. |
| `movie_rating`     | String          | MPAA rating of the movie (e.g., PG, PG-13, R).  |
| `duration_movie`    | String         | Duration of the movie in hours and minutes (e.g., 2h 5m).|
| `average_star_rating_movie` | Float   | Average user star rating of the movie on IMDb (scale of 1–10). |
| `vote_count_movie`  | Integer         | Total number of votes received on IMDb.      |
| `review_text`   | String            | Scraped user reviews from IMDb.|
| `book_authors`    | String           | Name(s) of the author(s) of the book.|
| `average_rating_book` | Float       | Average Goodreads rating of the book (scale of 1–5).  |
| `num_pages_book`    | Integer         | Total number of pages in the book. |
| `ratings_count_book`  | Integer       | Total number of user ratings the book received on Goodreads.|
| `publication_date_book` | String     | Date the book was originally published (in MM/DD/YY format).|
| `publisher_book`       | String      | Publisher of the book.|
