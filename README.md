# EDA-COVID-19 tweet-requin
## Introduction
### This repository contains the exploratory data analysis (EDA) of a COVID-19 tweets dataset. The analysis aims to understand the sentiment expressed in tweets.
## Dataset Overview
### The dataset includes following columns:
#### UserName: The user's name who posted the tweet.
#### ScreenName: The user's Twitter handle.
#### Location: The location provided by the user in their profile.
#### TweetAt: The date when the tweet was posted.
#### OriginalTweet: The full text of the tweet.
#### Sentiment: The sentiment expressed in the tweet (e.g., Positive, Negative, Neutral).
## Data Cleaning
### handling missing values: Location column had 21% missing values out of entire data.
### Converting datatype: changed TweetAt column from object type to datetime format.
## Data Analysis
### Sentiment Distribution- Bar plot and pie chart toshow thw unique sentiment values and proportions.
### Temporal Analysis - How sentiments change over time. Used time-series plot to show the distribution.
### Location Analysis - How sentiments change over geographical area. Used bar plot to show distribution over top 10 most tweeted locations.
### Tweet length Analysis - how tweet lengths vary with different sentiments. Used histogram and box plot to find the pattern as well as anomalies/outliers.
### Correlation Analysis - showa relationship between numerical variables in the dataset. Used correlation heatmap.
## Handling Outliers
### Used the Interquartile Range (IQR) method to detect and optionally remove outliers. 
