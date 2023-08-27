# Recommender system using collaborative filtering

In this project, we're building a recommendation system using collaborative filtering techniques. Collaborative filtering is a method commonly used in recommendation systems to make personalized recommendations by leveraging the preferences and behaviors of similar users.

## Data Preparation:

1.	We start by loading a dataset that contains user ratings for different products in the beauty category.
   
2.	We analyze the dataset to understand its characteristics, including the number of users, products, and ratings.

   
## User-Based Collaborative Filtering: 

3. We perform user-based collaborative filtering, which involves finding users who are similar in terms of their product preferences.

## Calculating Similar Users: 

4. We create a user-product matrix, where rows represent users and columns represent products. The values in this matrix are the normalized ratings that indicate how much a user's rating deviates from their average rating.

5.	We calculate the cosine similarity between users' rating vectors. Cosine similarity measures how similar two users are based on their product preferences.
   
## Selecting Similar Users: 

6. We identify the top k most similar users for a given user by sorting the similarity scores in descending order.
   
## Generating Recommendations:

7. For a specific user, we take the ratings of the top similar users and generate recommendations based on products that these similar users have liked.

## Evaluation:

8. We split the data into training and testing sets to evaluate the performance of our recommendation system.

9.	We calculate recommendations for specific users in the test set and compare these recommendations with the products they actually rated.
