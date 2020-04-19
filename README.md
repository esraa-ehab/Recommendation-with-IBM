# Recommendation-with-IBM

Recommendation-with-IBM
Make a recommendation engine using ranked based, user-user based collaborative filtering, content based, and matrix factorization

In this project I have analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations to them about new articles that I think they will like.

Your Tasks Your project will be divided into the following tasks

I. Exploratory Data Analysis
Before making recommendations of any kind, I explored the data that I was working with for the project. I Dove in to see what I could find. There are some basic, required questions that I answered about the data I am working with throughout the rest of the notebook.

II. Rank Based Recommendations
To get started in building recommendations, I first found the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it was easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, I looked at users that are similar in terms of the items they have interacted with. These items were then recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

IV. Content Based Recommendations
Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using NLP skills, I came up with some extremely creative ways to develop a content based recommendation system.

V. Matrix Factorization

Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using the decomposition, I got an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great). I finally discussed which methods I used moving forward, and how to test how well the recommendations are working for engaging users.
