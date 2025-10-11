# Goodreads_Book_Review
The Goodreads Book Review Project is about the analysis of books in goodreads website based on the reviews, books, author title and the genre.

# Objective
This project analyzes a Goodreads book reviews dataset to explore reader preferences, book popularity, and sentiment trends. Using SQL, I performed data celaning,exploratory data analysis to uncover insights anout genres, ratings and review patterns.

# 📂Dataset
Dataset Name: Goodreads Book Reviews
Source: MavenAnalytics - Goodreads Dataset[https://app.mavenanalytics.io/datasets]
# Files
File Name:goodreads_reviews.csv
This file contains information on reviews such as:
- review_id
- user_id
- work_id
- started_at
- read_at
- date_added
- rating
- review_text
- n_votes
- n_comments

File name:goodreads_works.csv
This file contains information on wroks done by the author such as:
- work_id
- isbn
- isbn13
- original_title
- author
- original_publication_year
- num_pages
- description
- genres
- image_url
- reviews_count
- text_reviews_count
- 5_star_ratings
- 4_star_ratings
- 3_star_ratings
- 2_star_ratings
- 1_star_ratings
- ratings_count
- avg_rating
- similar_books

# Business Insights to be identified
-What are the most popular books and authors? What about the most controversial?
-Which genres have the highest reader engagement? What are their most popular books?
-Who are the highest-rated authors? How have their works trended by publication year?
-Do longer reviews get more "helpful" votes? What about reviews with extreme ratings (1 or 5 stars)?

## Project Structure
``````
📦 GoodReads
├─ goodreads_data_dictionary.csv
├─ goodreads_reviews.csv
└─ goodreads_works.csv
```
