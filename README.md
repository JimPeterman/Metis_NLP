# Metis_NLP

The fourth project from my Metis Data Science Bootcamp centered around natural language processing and unnsupervised learning models.

I chose to scrape tweets from Twitter and build an unsupervised learning model to identify the primary topics that make up New Years resolutions and the general sentiment surrounding these tweets. The goal was to help wellness companies create relevant and supportive content for individuals to help them make lasting changes to improve their lives.

Initial topic modeling was performed/explored using CountVectorizer and TfidfVectorizer as well as LSA, NMF, and LDA. Using some of the terms identified in the exploratory analysis, CorEx was used to finalize the topics. 

Sentiment analysis was performed across the entire dataset and on each of the individual topics. The sentiment of the most popular tweets was also explored (most favorited, most retweeted). 

Figures were created to highlight the top terms associated with each topic (word clouds) and to highlight the different terms used between positive and negative tweets.


The finalized documents include:
- A Jupyter Notebook for the minimum viable product (MVP) assignment
- Jupyter Notebooks with the code for the project (scraping tweets from Twitter, topic modeling, and sentiment analysis)
- A brief writeup
- A short (5min) presentation of the project findings
- A scattertext plot
