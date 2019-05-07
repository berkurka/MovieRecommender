# ![]() Movie Recommender

## Project Author
- Bernard Kurka | <u>[LinkedIn](https://www.linkedin.com/in/bernardkurka)</u> | <u>[Email](bkexcel2014@gmail.com)</u>


## Notebooks
- <u>[Movie Recommender](https://github.com/berkurka/MovieRecommender/blob/master/Movie_Recommender.ipynb)</u>


### Executive Summary
I used Python to build item-based and user-based movie recommender systems using cosine similarity. In the Jupyter notebook I've created functions to run the recommendations based on user inputs.

### Data
The data set contained 100.000 movie ratings, produced by 600 users. The data included 9.000 movie titles and is available at the GroupLens Research website.

### Recommender

1. Item-Based Recommender.

   I built this recommender calculating cosine similarity between movies. The similarity was calculated using two vectors that contained movie ratings.

2. Item-Based and Genre Recommender:

  I added a new layer to the recommender, first I will find movies with similar genres and then select the best rating similarities.

3. User-Based Recommender:

  Using two vectors with each person's scores for the 9.000 movies, I am able to calculate the cosine similarity between these two users. My friend Bernardo rated 65 movies, I've imported his ratings and found the 4 users that had the most similar cosine similarity. And then calculated the mean score for each movie considering their rating.

### Evaluating Recommenders and Answering the problem:
I did not create an evaluation metric nor did build any statistics on its performance. I did manual explorations selecting multiple movies I've like and observed the results. In my blog, I've printed the recommendations for Iron Man 2(2010) and Inception (2010).

## Improving the recommender:
1. GroupLens has a bigger data set with more movies and user reviews, using this data would improve the cosine similarity recommenders.

2. To improve the user-based recommender it would be nice to have more reviews from my friend.

3. To evaluate the user-based recommender it's possible to separate the data into split and test in order to compare recommendations with actual scores from the user.

4. Using more qualitative information about each film might improve the recommender, such as movie's decade, main actor, director, length, and movie cost.

## Next Steps:
I will build an online dashboard where a person can select a movie and check out the recommendations.
