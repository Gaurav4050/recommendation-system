# gaurav

A content based movie recommender system using cosine similarity

About project : -

For this I took the tmdb dataset from Kaggle and did some data preprocessing. After data preprocessing I create tag section in my DataFrame which contains more than 5000 keywords of that particular movie.

After making that section I did vectorization operation on it and found out the cosine similarities between the movies.

The film that has the maximum cosine similarity, I recommended the movie to the user.
