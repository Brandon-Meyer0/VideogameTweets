# VideogameTweets
Team 5 Capstone Project

* [***Project Overview:***](#project-overview) The overall project goal and approach.
* [***Navigation Instructions:***](#navigating-the-repo) Guidance for how to navigate the repo.
* [***Data Science Steps:***](#data-science-steps) Summary of the steps our team took to arrive at our recommendation.

# Relevant Files

* [***Jupyter Notebook:***](TweetSentimentAnalysis.ipynb) Here's the link to our teams Jupyter Notebook. This notebook will walk through our analysis.
* [***Presentation:***](Group5CapstonePresentation.pptx) Here's the link to our teams presentation. It includes our recommendations and analysis findings.


# Project Overview

Multiplayer games rely on playerbase retention to be profitable in the long run, which is why updates are rolled out periodically. We want to measure the response of the playerbase towards said updates to be able to gauge the reception of these by creating an AI model that analyzes the sentiment of a tweet. Being able to know the reception of an update for a game you like seemed like an interesting idea, we belive this is a great opportunity to learn new tools, machine learning models and experiment with text data creating valuable results.


# Navigating the Repo
In this repo you will find the following:
-	This ReadMe.md file
-	Jupyter Notebook – Contains all relevant code used for our data analysis.
                   - Data File – Our team used 2 data-files a training set & validation set.
-	PowerPoint.pptx – This is the presentation of our analysis and findings.

# Data Science Steps
Below is a list of steps that our team took as well as the corresponding description. Since our goal is to predict if a comment on twitter is Positive, Negative or Neutral in order to provide feedback on what to do or what not to do to a game with an update, we'll need to clean our text data sets.

### 1.- Data Gathering and Cleaning
-	twitter_training.csv
-	twitter_validation.csv
Team conducted Exploratory Data Analysis on all the source files to identify data entries that are not valuable like duplicated and elements, special characters, emojis and entities. Team used Tokenization, Stemming, Lemmatization techniques to have a completed cleaned dataset.

### 2.- Modeling
