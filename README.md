# Tweeter Crawler


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Pythong Packages Used](#python-packages-used)
* [Features](#features)
* [Twitter API Setup](#twitter-api-setup)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)


## General Information
- This crawler allows users to scrape the profile, and social network (i.e., friends and followers) from the handle of a Twitter user of interest. It also scraps for the top 50 most popular tweets containing the keywords "coronavirus" and/or "vaccination".
- This project is an interim project assigned to learners as part of the Microsoft Business Intelligence and Data Analyst Course.


## Technologies Used
- PostgreSQL 9.5 or higher
- pgAdmin 4 5.1 or highe
- Python 3.8 or higher


## Python Packages Used
- Tweepy 3.10.0
- SQLAlchemy 1.3.19
- Pandas 1.2.4


## Features
This crawler has the ability to:
- find the twitter details of user of your choice
- find out who are the friends and followers of your chosen user
- extract tweets containing the keywords "coronavirus" and "vaccination"


## Twitter API Setup

You will need the following information for authentication with Twitter within the crawler in order to crawl data using Twitter API:

- API Key
- API Secret
- Access Token
- Access Token Secret
- Here are the steps to obtain them:

1. Create a Twitter account: https://twitter.com/i/flow/signup
2. Apply for a developer account: https://developer.twitter.com/en/apply-for-access
3. After your application is approved, create a Twitter Developer App.
4. Navigate to the App you just created and you will see a tab on “Keys and Tokens”. Clicking on the "Keys and Tokens" tab should show your API Key and Secret, as well as the Access Token and Secret.



## Project Status
Project is complete. Future versions with more advance capabilities are being considered.


## Room for Improvement
- Ablity to pull at least 1,000 tweets per run
- Allow the user to input keywords of their choice for tweets extraction
- Sentiment analysis of tweets extracted


## Acknowledgements
- This project was inspired and jointly developed with my amazing teammates Jacob, Tziqing, Weicheng and Yisheng.
- Special thanks to my instructors Calvin and Nelson for their valuable inputs and guidance.

