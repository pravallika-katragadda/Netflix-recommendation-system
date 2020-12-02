Netflix-Recommendation-System
This is a simple recommender system written completely in python using two datasets.

Install all dependencies as specified in the requirements.txt file.

## Run .ipynb in "Jupyter Notebook" or google colaboratory to check the code.

**************************
OVERVIEW:
**************************

Project aim is to provide recommendations its all about creating a netflix recommender systems using various algorithms and methods.
Main focus were using machine learning techniques that included K- means clustering using Adamic adar measure by plotting graph, Popularity-based filtering, Content-based filtering, Collaborative filtering and Hybrid filtering.

For detailed information check the Project report and pdf slides provided.

****************************
Algorithms overview
****************************
We have used and implemented: 

* K-means clustering with TF-IDF using Adamic Adar measure.

splitted, trained and tested the movies-dataset which contains 26 million ratings from 270,000 users for all 45,000 movies
and applied following recommender models:
* Demographic Filtering(Popularity based recommender)
* Content-based filtering- 1.Plot based recommender
			 2. Credits, cast, keywords based recommender.
* collaborative filtering- 1.Used matrix factorization method(sparsity)
			 2.SVD- for the prediction matrix
			 3.User-based filtering and
			 4.Item based filtering
* Hybrid Recommender


*************************
Sources for the dataset: 
*************************
Open source movie datasets are available on:
https://www.kaggle.com/rounakbanik/the-movies-dataset
https://www.kaggle.com/shivamb/netflix-shows

Other External sources:
https://grouplens.org/datasets/movielens/latest/

--------------------------
Datasets overview
--------------------------

These movies-dataset contains metadata for all 45,000 movies listed in the Full MovieLens Dataset.
This dataset has files containing 26 million ratings from 270,000 users for all 45,000 movies.
This dataset is an ensemble of data collected from TMDB and GroupLens.
The Movie Details, Credits and Keywords have been collected from the TMDB Open API. 
Dataset includes cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages.
Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.

Another dataset:contains titles of Tv shows/movies updated every month as of 2019.



