# Twitter Sentiment Analysis

This project analyzes the sentiment of tweets using the `cardiffnlp/twitter-xlm-roberta-base-sentiment` model from the `transformers` library.

## Dependencies

The following libraries are used in this project:
- pandas
- numpy
- matplotlib
- plotly
- seaborn
- yfinance
- re
- tqdm
- transformers
- datasets
- ast
- nltk
- wordcloud

## Data

The dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets/khalidryder777/500k-chatgpt-tweets-jan-mar-2023).

The data used in this project is a CSV file named `Twitter Jan Mar.csv`. The file contains tweets and their metadata.

## Preprocessing

The data is preprocessed by removing URLs, new line characters, mentions, hashtags, and punctuation. The text is also converted to lowercase.

## Sentiment Analysis

The sentiment of each tweet is analyzed using the `cardiffnlp/twitter-xlm-roberta-base-sentiment` model. The results are stored in a new DataFrame and saved to a CSV file named `Inference_results_V2.csv`.

## Data Analysis

The data is analyzed to find the most common words for positive, negative, and neutral tweets. The distribution of sentiment scores is also plotted. The evolution of sentiment scores over time is analyzed by day, week, and month. The number of tweets per day, week, and month is also plotted. The top 15 hashtags are also plotted.

## Word Cloud

A word cloud is generated using the lemmatized content of the tweets.
