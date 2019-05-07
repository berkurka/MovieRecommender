# ![]() Movie Recommender

## Project Author
- Bernard Kurka | <u>[LinkedIn](https://www.linkedin.com/in/bernardkurka)</u> | <u>[Email](bkexcel2014@gmail.com)</u>



## Notebooks
- <u>[01 Data Cleaning](https://github.com/berkurka/Mutual_Fund_Clustering/blob/master/Notebooks/Movie_Recommender.ipynb)</u>



### Executive Summary
I used Python to build a 3 movie recommender systems based on cosine similarity.

### Data
The data set contains 100.000 movie ratings, made by 600 users, the data contains 9.000 movie titles obtained the GroupLens Research website.

### Recommender

1. Item-Based Recommender.

  Was built calculating similarity between movies. The similarity was calculated using the cosine similarity between two vectors that contain each movies ratings.

2. Item-Based and Genre Recommender:

  I added a new layer to the recommender, first I will find movies with similar genres and then select the best rating similarities.

3. User-Based Recommender:

  Using two vectors with each person's scores for the 9.000 movies, I am able to calculate the cosine similarity between these two users. My friend Bernardo rated 65 movies, I've imported his ratings and found the 4 users that had the most similar cosine similarity. And then calculated the mean score for each movie considering their individual rating.

   q
