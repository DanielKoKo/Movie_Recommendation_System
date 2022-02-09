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
  
  ![image](https://user-images.githubusercontent.com/32584958/153116425-4cef22cd-8bc3-4f5b-96b8-ca241602f7fd.png)
  
* These are user 5's actual highest rated movies:
  
  ![image](https://user-images.githubusercontent.com/32584958/153116017-959336ec-84bb-41bb-bc7b-db1bf50c84cf.png)
  
  * movieId 1036: "Die Hard"
  * movieId 141: "Unusual Suspects"
  * movieId 1196: "Run Lola Run"
  * movieId 593: "Laputa: Castle in the Sky"
  
* All of these movies have mixtures of genres Action, Crime, Adventure, Mystery, Thriller, and Drama. So the predicted recommendations match user 5’s taste.


