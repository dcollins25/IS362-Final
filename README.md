# IS362-Final - Dan Collins

This project uses a dataset for Amazon's Top 100 Bestselling Books from https://www.kaggle.com/datasets

Key Features of the DataSet include:
 - Book Rank: The ranking of the book among the top 100 Bestselling books on Amazon.
 - Book Title: The title of the book.
 - Price: The price of the book in USD.
 - Rating: The overall rating of the book, on a scale of 1 to 5.
 - Author: The author of the book.
 - Year of Publication: The year in which the book was published.
 - Genre: The genre or category to which the book belongs.
 - URL: The URL link to the book on Amazon's platform.
 - Review Title: The title of the book review.
 - Reviewer: The name of the person who has written a review for the book.
 - Reviewer Rating: The rating given by the reviewer for the book, on a scale of 1 to 5.
 - Review Description: The text description of the review given.
 - Is_verified: Indicates whether the review is verified as a genuine customer review.
 - Date: The timestamp indicates the date when the review was posted.
 - Timestamp: The timestamp indicates when the review was posted.
 - ASIN: Amazon Standard Identification Number assigned to products on Amazon.

I loaded the dataset, which contains 2 .csv files, into a SQLite databse. I then query the database and use numerous modules including pandas, numpy, scikit, to load the data and analyze it to ask questions.