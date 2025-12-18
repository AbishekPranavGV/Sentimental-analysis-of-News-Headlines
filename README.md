# Sentimental-analysis-of-News-Headlines
Sentiment Analysis of News Headlines
This project performs real-time sentiment analysis and data clustering on financial news headlines. By scraping data for specific stock tickers and utilizing Natural Language Processing (NLP) techniques, the project provides insights into market sentiment trends.

# 🚀 Project Overview
The notebook demonstrates a complete data pipeline including:

Web Scraping: Retrieving recent financial news headlines for specific stocks (e.g., AMZN, GOOG, META) from Finviz.

Sentiment Analysis: Using the NLTK VADER (Valence Aware Dictionary and sEntiment Reasoner) to calculate "compound" sentiment scores for each headline.

Data Visualization: Plotting sentiment trends over time to identify shifts in market perception.

Text Clustering: Grouping similar headlines using TF-IDF Vectorization and K-Means clustering to identify common themes in news coverage.

🛠️ Requirements
The following libraries are required to run this project:

pandas

matplotlib & seaborn

nltk

beautifulsoup4

scikit-learn

spacy

Install them via pip:

Bash

pip install nltk beautifulsoup4 pandas matplotlib scikit-learn spacy gensim seaborn
python -m spacy download en_core_web_sm
📊 Key Features
VADER Sentiment Scoring: Automatically classifies headlines into positive, negative, or neutral categories based on a -1 to 1 scale.

Time-Series Analysis: Groups data by ticker and date to show the average sentiment progression across multiple trading days.

K-Means Clustering: Unsupervised learning used to categorize headlines into 3 distinct clusters based on text similarity.

# 📈 Sample Results
The analysis identifies specific sentiment peaks and troughs. For example:

High Sentiment: Headlines related to "Best Strong Buy Stock" (Score: ~0.8176).

Low Sentiment: Headlines discussing "Stock Drops Despite Market Gains" (Score: ~-0.2330).

# 📂 File Structure
Sentimental analysis of News Headlines.ipynb: The main Jupyter Notebook containing the source code and visual outputs.
