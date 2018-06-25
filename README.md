# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Predicting User Interaction on Reddit 

## Scenario 

Pitching a narrative on how to create a Reddit post that will get the most engagement from Reddit users by putting classification methods, webscraping, and Natural Language Processing skills to the test 

For this project, the following fundamental data science skills are practiced: 
- Using the Requests and Beautiful Soup libraries to collecting data by scraping a website 
- Build binary classification models to predict high user interaction Reddit posts  

## Project Summary

### Problem statement: 
_What characteristics of a post on Reddit are most predictive of the overall interaction on a thread (as measured by number of comments)?_

### Acquiring data: 
Scraping the 'hot' threads as listed on the [Reddit homepage](https://old.reddit.com/) to acquire the following pieces of information about each thread: 
1. The title of the thread
2. The subreddit that the thread corresponds to
3. The length of time it has been up on Reddit
4. The number of comments on the thread

### 1. Loading Data & Performing Basic Operations 
- Checking for null values, converting datatypes, and cleaning data to prepare for EDA.

### 2. Exploratory Data Analysis
- Investigating varibale distributions, frequencies, and relationships by compiling several visualizations and aggregate functions with the ultimate goal of selecting features to be used in the model building process

### 3. Model Building
- Transforming 'Title` and `Subreddits` columns into sparse predictor matrices via Count Vectorizer and Dummy Variables. 
- Accessing feature importances to identify predictive title words (of varying n-gram ranges) and Subreddits.
- Comparing the performance of Random Forest and Logistic Regression Models with cross-validated scores.
- Utilizing the components of confusion matrices to explore additional performance metrics, especially Sensitivity and Specificity. 
- Running a GridSearchCV to tune hyperparameters and optimize model performance. 

### 4. Executive Summary 

---

