# Reccomendations-IBM
Recommendation on data from the IBM Watson Studio platform
## Project Outline
There are three components in this project.

1. Exploratory Data Analysis

- Getting to know the data and developing data understanding.
- What is the distribution of how many articles a user interacts with in the dataset?
- The number of unique articles that have an interaction with a user.
- The number of unique articles in the dataset (whether they have any interactions or not).
- The number of unique users in the dataset. (excluding null values)
- The number of user-article interactions in the dataset.  
2. Rank Based Recommendations

- Find the most popular articles simply based on the most interactions.
- In the absence of ratings for any of the articles, assume the articles with the most interactions are the most popular.
- These are then the articles we might recommend to new users (or anyone depending on what we know about them).  
3. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.  
4. Matrix Factorization

- Using the user-item interactions, build out a matrix decomposition. Using decomposition, evaluate performance.
