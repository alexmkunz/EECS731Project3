# EECS 731 Project 3: Clustering Movies
Cluster movies based off of genre.

## Data Set
**https://grouplens.org/datasets/movielens/**: the data sets can be retrieved from this website. They were too big to host on Github.

## Juypter Notebook
**weekendMovieTrip.ipynb**:
 - **Exploratory Data Analysis:** determine genres will be useful, while tags are too niche to incorporate.
 - **Feature Engineering:**
   - One-hot-encode genres.
   - Add average rating and number of ratings for a movie.
   - Remove movies with less than 50 ratings.
 - **Clustering Models:**
   - K-Means Clustering
   - Agglomerative Clustering

## Conclusion
Agglomerative Clustering seemed to be more accurate.
