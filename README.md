# recommendations_with_ibm
udacity_nanodegree_course
Introduction
This project analyzes the interactions that users have with the articles on the IBM Watson Studio platform, and will help to make recommendations to the users about new articles which they will like.

IBM Watson
IMB Watson website : https://dataplatform.cloud.ibm.com/home?context=wdp



Project Overview
File : Recommendations_with_IBM.ipynb

I. Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. You should dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the whole notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most of all interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look deeply at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a huge step in the right direction towards more personal recommendations for the users. You will implement this for the next step.

IV. Content Based Recommendations

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

V. Matrix Factorization

Finally, you are going to complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.
