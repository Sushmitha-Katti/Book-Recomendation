# BOOK RECOMENDATION SYSTEM

We see the use of recommendation systems all around us. These systems are personalizing our web experience, telling us what to buy (Amazon), which movies to watch (Netflix), whom to be friends with (Facebook), which songs to listen (Spotify) etc. These recommendation systems leverage our shopping/ watching/ listening patterns and predict what we could like in future based on our behavior patterns. The most basic models for recommendations systems are **collaborative filtering** models which are based on **assumption that people like things similar to other things they like, and things that are liked by other people with similar taste**.

## Types Of Collaborative Filtering

![alt text](https://github.com/Sushmitha-Katti/Book-Recomendation/blob/master/Typesofcollabrativefiltering.png "Types Of Recomendation System")

### Items based collabrative Filtering
![alt text](https://github.com/Sushmitha-Katti/Book-Recomendation/blob/master/bookrecomendation.png "Example for Book Recomendation")

___
## Install:
___
  *Numpy
  *Pandas
  *Sklearn

You will also need to have software installed to run and execute a Jupyter Notebook.
If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

## Dataset:
___
[Here is the link for the dataset](https://www.kaggle.com/zygmunt/goodbooks-10k)

## Code:
___
Implementation of Book Recomendation System is provided in Book Recomendation.ipyn file inside the code folder.

## Run:
___
`In a anaconda promt or in the terminal, navigate to the code folder and run one of the following commands:
jupyter notebook "malicious_site_detection.ipynb"`

## Tables Used For Recommendation:
___
  *Ratings.csv
  *Books.csv

## Algorithm Used:
___
Cosine Similarity - Calculated the closest user or item.

## Input:
___
	`getTopRecommandations(123)`

## Output:
___
Calculates top 5 related to the given Book

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

