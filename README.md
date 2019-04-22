# BOOK RECOMENDATION SYSTEM

We see the use of recommendation systems all around us. These systems are personalizing our web experience, telling us what to buy (Amazon), which movies to watch (Netflix), whom to be friends with (Facebook), which songs to listen (Spotify) etc. These recommendation systems leverage our shopping/ watching/ listening patterns and predict what we could like in future based on our behavior patterns. The most basic models for recommendations systems are **collaborative filtering** models which are based on **assumption that people like things similar to other things they like, and things that are liked by other people with similar taste**.

## Types Of Collaborative Filtering

![alt text](https://github.com/Sushmitha-Katti/Book-Recomendation/blob/master/Typesofcollabrativefiltering.png "Types Of Recomendation System")

### In Our project We are Using Memory Based Collaborative Filtering
**Memory-Based Collaborative Filtering** approaches can be divided into two main sections: **user-item** filtering and item-item filtering. A user-item filtering takes a particular user, find users that are similar to that user based on similarity of ratings, and recommend items that those similar users liked. In contrast, **item-item** filtering will take an item, find users who liked that item, and find other items that those users or similar users also liked. It takes items and outputs other items as recommendations.

Item-Item Collaborative Filtering: “Users who liked this item also liked …”

User-Item Collaborative Filtering: “Users who are similar to you also liked …”

## Item Based Book Recommendation:
We are implementating a item based Collabrative Filtering that determines the similar book for a given book.
![alt text](https://github.com/Sushmitha-Katti/Book-Recomendation/blob/master/bookrecomendation.png =250x250)


## Install:

  * Numpy
  * Pandas
  * Sklearn

You will also need to have software installed to run and execute a Jupyter Notebook.
If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

## Dataset:

[Here is the link for the dataset](https://www.kaggle.com/zygmunt/goodbooks-10k)

## Code:

Implementation of Book Recomendation System is provided in Book Recomendation.ipyn file inside the code folder.

## Run:

`In a anaconda promt or in the terminal, navigate to the code folder and run one of the following commands:
jupyter notebook "malicious_site_detection.ipynb"`

## Tables Used For Recommendation:

  * Ratings.csv
  * Books.csv

## Features of ratings.csv:
	* user_id - Unique Id Of User
	* book_id - Unique Id of Book
	* rating - Rating of the Book by user

## Algorithm Used:

**Cosine Similarity** - It is the cosine of the angle between two n-dimensional vectors in an n-dimensional space. It is the dot product of the two vectors divided by the product of the two vectors' lengths (or magnitudes).
![alt text](https://github.com/Sushmitha-Katti/Book-Recomendation/blob/master/cosine-similarity.png "Cosine-Similarity")


## Input:

Takes the book id as input.

	`getTopRecommandations(123)`

## Output:

Calculates top 5 related books to the input book.

`------INPUT BOOK--------

Title: The Firm

Author: John Grisham

Printing Book-ID: 123

=================++++++++++++++=========================

-------RECOMMENDATIONS----------

Title: The Pelican Brief

Author: John Grisham

Printing Book-ID: 281

=================++++++++++++++=========================

Title: Angels & Demons 

Author: Dan Brown

Printing Book-ID: 9

=================++++++++++++++=========================

Title: The Client

Author: John Grisham

Printing Book-ID: 227

=================++++++++++++++=========================

Title: Divine Secrets of the Ya-Ya Sisterhood

Author: Rebecca Wells

Printing Book-ID: 136

=================++++++++++++++=========================

Title: The Secret Life of Bees

Author: Sue Monk Kidd

Printing Book-ID: 57

=================++++++++++++++=========================`

