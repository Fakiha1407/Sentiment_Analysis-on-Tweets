# Sentiment_Analysis-on-Tweets
# Tweet Sentiment Analysis

This project classifies tweets as **positive**, **neutral**, or **negative** using TextBlob.


## Pipeline Steps
1. **Load data** from `kaggle`.
2. **Preprocess** tweets: lowercase, remove URLs, non-letters, extra spaces.
3. **Analyze sentiment** with TextBlob polarity: >0 positive, <0 negative, =0 neutral.
4. **Visualize** distribution with a bar chart.
5. **Save** results to `output/sentiment_analyzed_data.csv`.

# Quickstart
```bash
git clone https://github.com/<your-username>/TweetSentimentAnalysis.git
cd TweetSentimentAnalysis
pip install -r requirements.txt
python src/sentiment_analysis.py
# or open Jupyter:
jupyter notebook notebooks/Tweet_Sentiment_Analysis.ipynb
```

# Requirements
- pandas
- textblob
- matplotlib
- tqdm  _(for displaying progress bars during sentiment analysis)_

