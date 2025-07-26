Project Overview<br>

This project focuses on analyzing public sentiment on social media (Twitter) using Natural Language Processing (NLP). The goal is to classify tweets into positive, negative, or neutral sentiments, helping brands and organizations understand public opinion and engagement.

Dataset Details:-

Total Rows: 162,980

Total Columns: 2

Columns:

clean_text: Preprocessed tweet text (cleaned of URLs, mentions, and special characters)

category: Sentiment label

-1: Negative sentiment

0: Neutral sentiment

1: Positive sentiment

Missing Values: 11 entries with missing data (should be cleaned before training).

Key Steps in the Project:-

i.Data Cleaning & Preprocessing

ii.Removed stop words, punctuation, and irrelevant text.

iii.Handled missing values and normalized text for analysis.

iv.Exploratory Data Analysis (EDA)

v.Visualized sentiment distribution across tweets.

vi.Analyzed frequently used positive and negative words using word clouds.

vii.Model Building

Converted text into numeric features using TF-IDF and Bag-of-Words.

Trained classification models (Logistic Regression, Naive Bayes, and Random Forest).

Evaluated model performance using accuracy, precision, recall, and F1-score.

Outcome:-

A robust sentiment classification model capable of categorizing tweets into positive, neutral, and negative sentiments.

Insights into public sentiment trends for further decision-making.

