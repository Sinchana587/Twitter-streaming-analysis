# Twitter_Streaming_analysis
# 🐦 Twitter Streaming Analysis

A real-time Twitter data pipeline built to collect, process, analyze, and visualize live tweets using Twitter's Streaming API and modern data engineering tools.

## 🚀 Key Features

- **Live Tweet Streaming**: Captures real-time tweets using Twitter API (v2).
- **Keyword/Hashtag Tracking**: Filter tweets based on keywords, hashtags, or user mentions.
- **Preprocessing Pipeline**: Cleans and processes tweet text (removes stopwords, handles emojis, hashtags, links).
- **Sentiment Analysis**: Classifies tweets into Positive, Negative, or Neutral using NLP models.
- **Word Cloud & Hashtag Analysis**: Generates word clouds and analyzes trending hashtags in real time.
- **Data Storage**: Tweets stored in CSV/JSON formats or streamed to a database for batch processing.
- **Visual Analytics**: Graphical representation of sentiments, tweet volume, user activity using Python visual libraries.
- **Modular Codebase**: Easy to modify or extend with additional analytics or storage tools (e.g., Kafka, MongoDB, Elasticsearch).

## 🧰 Technologies Used

| Category            | Tools / Libraries                      |
|---------------------|----------------------------------------|
| 🐍 Programming       | Python 3.x                              |
| 🔄 API & Streaming   | Tweepy (Twitter API wrapper)           |
| 🧠 NLP & ML          | TextBlob / VaderSentiment              |
| 📊 Visualization     | Matplotlib, Seaborn, WordCloud         |
| 🧼 Preprocessing      | NLTK, regex, pandas                    |
| 💾 Storage           | CSV, JSON (optional DB integration)    |
| 🛠️ Others            | dotenv for credential management        |

## 📁 Project Structure

