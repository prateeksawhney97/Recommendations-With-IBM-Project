# Recommendations-With-IBM-Project

### Building A Recommendation Engine With IBM!

##### This project is a part of the Data Scientist Nanodegree by Udacity. It features an important collaboration with IBM, the provider of the dataset. The aim is to develop a recommendation engine and suggest new articles to the IBM Watson Community users.

##### Libraries Used:

* Python 3.7 and above
* Pandas
* Numpy
* Matplotlib
* pickle
* RE
* NLTK
* Sklearn
* Jupyter

#### Overview
###### I. Exploratory Data Analysis
Before making recommendations of any kind, we will need to explore the data we are working with for the project. There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook.

###### II. Rank Based Recommendations
To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

###### III. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

###### IV. Content Based Recommendations
Given the amount of content available for each article, there are a number of different ways in which a content based recommendation system can be implemented. 

###### V. Matrix Factorization
Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using the decomposition, we will get an idea of how well we can predict new articles an individual might interact with. We will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.
