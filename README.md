# 20230505_ChatGPT on Reddit_Unveiling Sentiments & Buzzing Topics

- Latest Updated: 20230505
- Readme Edited: 20231209

- Author: Yunhao Li\*, Siheng Huang, Yanhan Chen, Yicong Li

- Description: This project is a group project, which conducts a sentimental analysis on the ChatGPT comments on Reddit using R. We concerns three questions: 
	(1) How does public attitude toward ChatGPT evolve over time? (Sentiment analysis)
	(2) What are the users’ primary concerns with ChatGPT? (Topic modeling)
	(3) What awaits human beings as the AI revolution unfolds?
	- Forked from lizzy-sc/597-Final-Project: https://github.com/lizzy-sc/597-Final-Project

 - Data Description
	- With Reddit API, we scrape 4 months' (Dec. 2022 - Mar. 2023) worth of data from the 5 (tentative, depends on the size) most popular subreddits related to ChatGPT and perform NLP to determine the primary concerns of the users.
	
- Relevant packages
	tidyverse, lubricate, stringr, purrr, tidytext, textdata, tm, topicmodels, rvest, jsonlite, redditExtractoR, etc.