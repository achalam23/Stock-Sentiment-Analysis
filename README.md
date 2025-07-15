# Stock Tweet Sentiment Analysis to Predict Stock Price Movement
This project evaluates the performance of different sentiment classifers and ML models in terms of predicting whether a company stock will go up or down on a certain day

## Dataset

Obtained from Kaggle: [Stock Tweets for Sentiment Analysis and Prediction](https://www.kaggle.com/datasets/equinxx/stock-tweets-for-sentiment-analysis-and-prediction)

### Sentiment Classification Models:

[FinBERT](https://huggingface.co/ProsusAI/finbert)

[VADER](https://github.com/cjhutto/vaderSentiment)

[RoBERTa](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest)

[Emotion English DistilRoBERTa](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base)

## Setup

##Requires Python 3.11 — not compatible with Python 3.13+

## Create Python Virtual Environment

```bash
python -m venv venv
```

## Activate Virtual Environment

### macOS/Linux

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate.ps1
```

## Install Packages

```bash
pip install -r requirements.txt
```

