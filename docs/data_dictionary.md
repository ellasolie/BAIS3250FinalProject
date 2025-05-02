# Data Dictionary
| Column Name               | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `title`                   | Shared title of the book and its movie adaptation (standardized for merge) |
| `imdb_id`                 | Unique IMDb identifier used for scraping movie data                        |
| `release_year_movie`      | Year the movie was released                                                 |
| `movie_rating`            | MPAA movie rating (e.g., PG, PG-13, R)                                      |
| `duration_movie`          | Runtime of the movie (e.g., '2h 15m')                                       |
| `average_star_rating_movie` | Average IMDb user rating of the movie (out of 10)                         |
| `vote_count_movie`        | Total number of votes received on IMDb                                      |
| `review_text`             | Scraped user review from IMDb                                               |
| `book_authors`            | Author(s) of the book (multiple separated by `/`)                           |
| `average_rating_book`     | Average Goodreads user rating of the book (out of 5)                        |
| `num_pages_book`          | Total number of pages in the book                                           |
| `ratings_count_book`      | Total number of Goodreads ratings the book received                         |
| `publication_date_book`   | Publication date of the book (in MM/DD/YY format)                           |
| `publisher_book`          | Publisher of the book                                                       |
