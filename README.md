# What's the matter?

The aim of this project is to collect and analyze Twitter data on an ongoing basis to discover the topics that people have been concerned about in the previous 7 days using the Twitter API recent search end-point.

# Project Outline

## 1. Data Collection

To begin prototyping, we extracted 20,000 tweets from the past 7 days using the following restrictions:

- the tweets are in English (`lang:en`)
- the tweets contain the following keywords:
> fear, fearful, afraid, scared, terrified, worry, worried, anxiety, anxious, distress, concern, dismay, strain,  stress, tension
- the tweets do not contain the following phrases:
> "nothing to fear", "fear not", "don't worry", "no worries"

## 2. Data Exploration & Visualization

A deeper dive into the text, tweets, and user data aimed at uncovering:
- the distribution of tweet & user metrics in the extracted data (typically exponential)
- the extent of time captured by the initially extracted data (~30-40 minutes worth of tweets)
- relationships between tweet metrics & user metrics (in progress)
- common words used in the extracted tweets, user names, and user descriptions (to be re-evaluated post-processing)
