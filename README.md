#Project: Recommendation System for Yelp Users
### Aim: The purpose of this project is create a recommendation system  based on user's review text and star ratings for restaurants in Las Vegas with the data provided by Yelp Data Challenge.

### Data: There are 2.7 reviews, 86K businesses, 649K reviews 10 cities across 4 countries. <https://www.yelp.com/dataset_challenge/dataset>

### Methods: 
1. Content-based filtering: 
  - A. Mapping restaurants and reviewers into a feature space and compute distance between restaurants and reviwers using dot products. And predict rating with linear model. 
  - B. Mapping review texts into feature space and recommed restaurant with similar text reviews to reviews. (different notebook)
  
  
2. Collaborative filtering: 
  - A. Item-based: Compute similarity between restaurants, recommend restaurants most similar to reviewer's item.
  - B. Model-based: Use restaurant categories to create latent variables in the rating data. Ratings are comoputed by dot products of users & items vectors in the latent feature space.
