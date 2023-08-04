
# VideogameTweets
Team 5 Capstone Project
# Capstone Repository for "Capstone Group 5" (GROUP 5)

# Project Overview

Multiplayer games rely on playerbase retention to be profitable in the long run, which is why updates are rolled out periodically. We want to measure the response of the playerbase towards said updates to be able to gauge the reception of these by creating an AI model that analyzes the sentiment of a tweet. Being able to know the reception of an update for a game you like seemed like an interesting idea, we belive providing leading and in-time insights to videogame developers to help them thrive in an accelerating market is a great opportunity as practical example in data science to learn and use new tools. 

This is the project repository for the capstone group 5 consisting of:

- [**Jahnavi Brahmbhatt**](https://github.com/Brandon-Meyer0/VideogameTweets/tree/Jahnavi)
- [**Brandon Cancino**](https://github.com/Brandon-Meyer0/VideogameTweets/tree/Brandon)
- [**Landon Steele**](https://github.com/Brandon-Meyer0/VideogameTweets/tree/landon-2)
- [**Miguel Cruz Le Hardy**](https://github.com/Brandon-Meyer0/VideogameTweets/tree/Miguel)
- [**Patricio Solorio Cabrera**](https://github.com/Brandon-Meyer0/VideogameTweets/tree/patricio)
  
*Links to each of the team member's repositories.

* [***Navigation Instructions:***](#navigating-the-repo) Guidance for how to navigate the repo.
* [***Data Science Steps:***](#data-science-steps) Summary of the steps our team took to arrive at our recommendation.

### Relevant Files

* [***Jupyter Notebook:***](TweetSentimentAnalysis.ipynb) Here's the link to our teams Jupyter Notebook. This notebook will walk through our analysis.
* [***Presentation:***](Group5CapstonePresentation.pptx) Here's the link to our teams presentation. It includes our recommendations and analysis findings.



## Business Understanding

Our key business variable for this study is *profit*; we want to help XYZ in making the correct decision when looking to make improvements and higher quality business decisions. 
The main questions we will be answering will be:










# Navigating the Repo
In this repo you will find the following:
-	This README.md file
-	Jupyter Notebook – Contains all relevant code used for our data analysis: Data Files – Our team used 2 data-files a training set & validation set.
-	PowerPoint.pptx – This is the presentation of our analysis and findings.

# Data Science Steps
Below is a list of steps that our team took as well as the corresponding description. Since our goal is to predict if a comment on twitter is Positive, Negative or Neutral in order to provide feedback on what to do or what not to do to a game with an update, we'll need to clean our text data sets.

### 1.- Data EDA & Cleaning
Team conducted Exploratory Data Analysis on all source files to identify data entries that are not valuable as duplicated and null elements, special characters, emojis and entities in text. Team followed Natural Language Processing steps creating Bag of Words for Frequency Distributions and Bigrams/Trigrams Mutual Information Scores for analysis, Tokenization, Stemming, Lemmatization and finally as Vectorization Strategie TF-IDF Vectorization to craft a fully workable cleaned dataset in order to run analysis from.
-	twitter_training.csv
-	twitter_validation.csv

### 2.- ML Modeling 
We decided to build our Models targeted to Tweet sentiment: Whether the discourse surrounding the game is overall positive, negative or neutral and whether it’s tied to an update for the game to provide developers with real-time feedback and sentiment analysis on their games from one of the most popular social media platforms around us. Using Neural Networks, Decision trees and Multi-Class Logistical Regression to determine our results and conclutions.

### 3.- Implementing Pipelines 
Team is confident in integrating ML pipeline​s in code in order to improve automation, scalability, efficiency, monitoring, and flexibility​ with the objective of providing in-time feedback to developers​ to work on the game so that with these insights in hand they are able to maintain or obtain new consumers to their product.
