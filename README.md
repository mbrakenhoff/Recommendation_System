# Amazon Product Recommendation System Project

## Context
This project was completed for the MIT Professional Learning Course, **Data Science and Machine Learning: Making Data-Driven Decisions**. In the age of information overload, consumers are often overwhelmed by the sheer volume of choices available online. Recommender systems are invaluable in helping consumers discover products that match their preferences, thereby enhancing their shopping experience and driving business growth. E-commerce giants like Amazon leverage sophisticated recommendation algorithms to provide personalized product suggestions.

## Objective
As a Data Science Manager at Amazon, your task is to build a recommendation system to suggest products to customers based on their previous ratings of other products. Using a collection of labeled data from Amazon reviews, the goal is to extract meaningful insights and build a recommendation system that enhances the shopping experience for online consumers.

## Dataset
The dataset, `ratings_Electronics.csv`, contains the following attributes:
- **userId**: Unique identifier for each user
- **productId**: Unique identifier for each product
- **rating**: Rating given by the user to the product
- **timestamp**: Time of the rating (not used in this project)

The dataset consists of 7,824,482 observations. To make it computationally feasible, we filter the dataset to include users who have given at least 50 ratings and products that have received at least 5 ratings, resulting in 65,290 observations.

## Conclusion
- Each model performs strongly with slight variations in metrics.
- The tuned SVD model shows the best overall performance.
- A hybrid recommendation system can be considered to leverage the strengths of each model type for different scenarios.

This project demonstrates how to build a robust product recommendation system using collaborative filtering and matrix factorization techniques. The tuned models provide accurate and personalized product recommendations, enhancing the shopping experience for Amazon's customers.
