# Project Description
## Tasks
- Find the number of books released after January 1, 2000.
- Find the number of user reviews and the average rating for each book.
- Identify the publisher that has released the greatest number of books with more than 50 pages (this will help you exclude brochures and similar publications from your analysis).
- Identify the author with the highest average book rating: look only at books with at least 50 ratings.
- Find the average number of text reviews among users who rated more than 50 books.

## Description of the data
`books`:
- book_id
- author_id
- title
- num_pages — number of pages
- publication_date
- publisher_id

`authors`:
- author_id
- author

`publishers`:

- publisher_id
- publisher

`ratings`:
- rating_id
- book_id
- username — the name of the user who rated the book
- rating

`reviews`:
- review_id
- book_id
- username — the name of the user who reviewed the book
- text — the text of the review