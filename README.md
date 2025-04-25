# Sentiment-Analysis-on-Twitter-Data-using-ML

This project performs sentiment analysis on real-time tweets using Tweepy for data collection and Machine Learning (Logistic Regression, SVM) for classification. The tweets are processed with NLTK, TextBlob, and VADER for initial labeling, and vectorized using TF-IDF. Final results are visualized with Matplotlib, Seaborn, and WordCloud.

## 📌 Key Features

- 🔁 Real-time Twitter data extraction via Tweepy
- 🧹 Preprocessing: stopword removal, tokenization, lemmatization
- 💬 Sentiment labeling with TextBlob and VADER
- 🧠 TF-IDF vectorization for feature extraction
- 🤖 Machine Learning with Logistic Regression and SVM
- 📈 Visualization: WordClouds, Sentiment Distribution
- ✅ Model evaluation: accuracy, confusion matrix, precision, recall

## 🧰 Libraries Used:
- `tweepy` – Access Twitter API
- `pandas`, `numpy` – Data manipulation
- `nltk` – Text preprocessing
- `textblob`, `vaderSentiment` – Sentiment scoring
- `scikit-learn` – Machine learning models and evaluation
- `matplotlib`, `seaborn`, `wordcloud` – Data visualization

## 📁 Data
The dataset is pulled directly from Twitter using the Tweepy API.

## 🤖 Example Predictions

Tweet	                      Sentiment
- "I love this!"	            Positive
- "This is terrible."	        Negative
