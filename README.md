# Movie_Recommendation_System
This is a Python-based movie recommendation system that suggests movies to users based on their existing reviews.

## Project Description
* This program uses the MovieLens dataset to recommend movies by considering not only user reviews, but also the genres of the highest rated movies.
  * The MovieLens dataset contains more than 20 million user ratings and 62,000 movies ranging from 1995 to 2019.
  ![image](https://user-images.githubusercontent.com/32584958/153115879-441c2fc6-f4e2-4b66-b765-a53012026e68.png)
* We clean the dataset by limiting to only 20,000 movies and 6,738 users, with each user having at least 20 ratings for separate movies to maximize the predictions' accuracy.
* We use K-Nearest Neighbors with cosine similarity to implement the bulk of the recommendation system. 

## Demo
* If we choose user 5 to recommend movies to, these are the movies that are predicted to have the highest ratings:
  ![image](https://user-images.githubusercontent.com/32584958/153116017-959336ec-84bb-41bb-bc7b-db1bf50c84cf.png)
  
* These are the predicted movies with their respective titles and genres:
  ![image](https://user-images.githubusercontent.com/32584958/153116118-d9b98a24-d626-47fa-93c3-85b4baf5dc12.png)
  
* User 5’s actual highest rated movies include “Unusual Suspects”, “Run Lola Run”, “Laputa: Castle in the Sky”, and “Sink the Bismark!”, all of which have mixtures of
genres Action, Crime, Adventure, Mystery, Thriller, and Drama. So the predicted recommendations match user 5’s taste.


