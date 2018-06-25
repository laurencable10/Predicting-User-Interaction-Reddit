# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Predicting User Interaction on Reddit 

## Scenario 

Pitching a narrative on how to create a Reddit post that will get the most engagement from Reddit users by putting classification methods, webscraping, and Natural Language Processing skills to the test 

For this project, two major data science skills will be practiced: Collecting data by scraping a website and building classification models to predict "viral" Reddit posts by creating a binary variable. 

## Project Summary

### Problem statement: 
_What characteristics of a post on Reddit are most predictive of the overall interaction on a thread (as measured by number of comments)?_

### Acquiring data: 
Scraping the 'hot' threads as listed on the [Reddit homepage](https://old.reddit.com/) to acquire the following pieces of information about each thread: 
1. The title of the thread
2. The subreddit that the thread corresponds to
3. The length of time it has been up on Reddit
4. The number of comments on the thread

### Model building: 
Building classification models using Natural Language Processing tools and any other relevant features to predict whether or not a given Reddit post will have above or below the median number of comments.

---

## Overview

1. Scrape "hot" threads from Reddit.come, utilizing the BeautifulSoup library to extract and prepare desired information
2. Exploratory Data Analysis 
3. Model building- comparing the performace of Random Forest and Logistic Regression models, as well as adding additional value through GridSearchCV and CountVectorizer
4. Delivering an executive summary of the results found
