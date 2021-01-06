# Sentiment Analysis - US Elections 2020

Since the 2020 US election has happened on the 3rd November 2020 and the resulting impact to the world will no doubt be large, so we have planned to do sentiment analysis for US 2020 elections with LSTM and GNN! 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sydney-machine-learning/sentimentanalysis-USelections/blob/main/main.ipynb)

## Dataset:
- [Data set](https://drive.google.com/drive/folders/1LnNvtOUWsfOwG8-tqAWaGvle3mcP52KR?usp=sharing) (Oct 15th 2020 - Nov 8th 2020, 1.72M Tweets)

## Refrences:
- [UK General Election 2017: a Twitter Analysis](https://arxiv.org/abs/1706.02271)
- [Location-based Sentiment Analyses and Visualization of Twitter Election Data](https://dl.acm.org/doi/fullHtml/10.1145/3339909)
- [USA NOV.2020 ELECTION 20 MIL. TWEETS (WITH SENTIMENT AND PARTY NAME LABELS) DATASET](https://ieee-dataport.org/open-access/usa-nov2020-election-20-mil-tweets-sentiment-and-party-name-labels-dataset#files)
- [PREDICTION OF USA NOVEMBER 2020 ELECTION RESULTS USING MULTIFACTOR TWITTER DATA ANALYSIS METHOD](https://arxiv.org/ftp/arxiv/papers/2010/2010.15938.pdf)
- 	[BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
- [LSTM vs BERT](https://towardsdatascience.com/lstm-vs-bert-a-step-by-step-guide-for-tweet-sentiment-analysis-ced697948c47)

#### Inspirations

- Can we predict the election outcome of each state.
- Can we predict the candidate from tweet text only.
- Can we detect if there are or were any attempts at manipulating the election.

#### CSV Columns description

```
created_at: Date and time of tweet creation
tweet_id: Unique ID of the tweet
tweet: Full tweet text
likes: Number of likes
retweet_count: Number of retweets
source: Utility used to post tweet
user_id: User ID of tweet creator
user_name: Username of tweet creator
user_screen_name: Screen name of tweet creator
user_description: Description of self by tweet creator
user_join_date: Join date of tweet creator
user_followers_count: Followers count on tweet creator
user_location: Location given on tweet creator's profile
lat: Latitude parsed from user_location
long: Longitude parsed from user_location
city: City parsed from user_location
country: Country parsed from user_location
state: State parsed from user_location
state_code: State code parsed from user_location
collected_at: Date and time tweet data was mined from twitter
```

