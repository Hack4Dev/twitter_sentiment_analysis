# Sentiment Analysis of Tweets  

## Description

Welcome to the project on Natural Language Processing and sentiment analysis of Twitter data! From the tutorials you will learn the following:

- *Tutorial 1* Collect and Clean Twitter Data
- *Tutorial 2* Perform sentiment analysis using existing toolkits
- *Tutorial 3* Perform sentiment analysis using machine learning

This project involves classical machine learing as well as transfer learning and therefore will suit participants who have some prior Python programming experience and a keen ineterst in machine learning. This project will also require additional computing resources. The use of a GPU is recommended (see [Google Colab](https://colab.research.google.com/)).


## Data

The dataset consists of 2000 tweets collected from a dataset called [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140), which contains 1.6 million general tweets and their corresponding sentiment labels.
This project makes use of supervised machine learning, therefore the data have all been assigned sentiment labels, i.e. either 0 or 1 corresponding to tweets with either negative or positive sentiment, respectively. 

In order for you to run the code in Tutorial 1 which allows you to collect tweets, you will need to set up a Twitter developer account and obtain certain API authorisation credentials. This can be done by followin g the instructions set out in the [Twitter API v2 setup.pdf](https://github.com/Hack4Dev/twitter_sentiment_analysis/blob/master/Twitter%20API%20v2%20setup.pdf) file.

## Hackathon Task

Think of a research question where sentiment analysis can be used to gain insight into a topic of interest!  

For example: What are people's sentiment toward a product, situation, disease or their government, in various countries? Think of what insights you would like to obtain around your research question. Be as creative as you'd like!  

You will need to:  

- Collect Twitter data from one or multiple regions in the world, relevant to your research question.  
- Prepare the data (by cleaning and/or pre-processing).  
- Make use of existing sentiment analysis tools or one of the trained machine learning models to predict sentiment of your collected tweets.  
- Draw some conclusions and present your findings.

## Prerequisites

All the libraries/dependencies necessary to run the tutorials are listed in the [requirements.txt](https://github.com/Hack4Dev/twitter_sentiment_analysis/blob/master/requirements.txt) file.


## Installation

All the required libraries can be installed using pip and the [requirements.txt](https://github.com/Hack4Dev/twitter_sentiment_analysis/blob/master/requirements.txt) file in the repo:

```bash
> pip install -r requirements.txt
```

### Would you like to clone this repository? Feel free!

```bash
> git clone https://github.com/Hack4Dev/twitter_sentiment_analysis.git
```

Then make sure you have the right Python libraries for the tutorials. 


### New to Github?

The easiest way to get all of the lecture and tutorial material is to clone this repository. To do this you need git installed on your laptop. If you're working on Linux you can install git using apt-get (you might need to use sudo):

```
apt install git
```

You can then clone the repository by typing:

```
git clone https://github.com/Hack4Dev/twitter_sentiment_analysis.git
```

To update your clone if changes are made, use:

```
cd twitter_sentiment_analysis/
git pull
```

-----
