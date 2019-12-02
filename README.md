# Recommendation-in-IBM-community

## Introduction
For this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make 
recommendations to them about new articles I think they will like. Below you can see an example of what the dashboard could look 
like displaying articles on the IBM Watson Platform.

![screen-shot-2018-09-17-at-3 40 30-pm](https://user-images.githubusercontent.com/36822899/58015252-10dfe780-7afb-11e9-9fd8-35de9f4ad142.png)


Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows
the articles that are most pertinent to a specific user. In order to determine which articles to show to each user, I will be performing 
a study of the data available on the IBM Watson Studio platform.

## What does the project contain?

> I. Exploratory Data Analysis

Before making recommendations of any kind, I will need to explore the data I am working with for the project. Dive in to see what I 
can find. There are some basic, required questions to be answered about the data I am working with throughout the rest of the notebook. 
I will use this space to explore, before diving into the details of the recommendation system in the later sections.

> II. Rank Based Recommendations

To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since 
there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are 
then the articles we might recommend to new users (or anyone depending on what we know about them).

> III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items 
they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards 
more personal recommendations for the users. You will implement this next.


> IV. Matrix Factorization

Finally, I will complete a machine learning approach to building recommendations. Using the user-item interactions, I will build out a 
matrix decomposition. Using the decomposition, you will get an idea of how well I can predict new articles an individual might interact 
with (spoiler alert - it isn't great). I will finally discuss which methods you might use moving forward, and how I might test how well
the recommendations are working for engaging users.
