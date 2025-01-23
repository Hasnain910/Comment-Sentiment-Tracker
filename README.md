# Comment-Sentiment-Tracker

Sentiment Analysis for Product Comments
This Python script performs sentiment analysis on user comments to classify them as Positive, Negative, or Neutral based on the presence of predefined positive and negative words. It processes text data, calculates sentiment scores, and outputs the sentiment and score for each comment.

Features:

Preprocessing: Converts comments to lowercase and removes non-alphabetic characters.
Sentiment Scoring: Compares occurrences of positive and negative words to calculate the sentiment score.
Classification: Assigns each comment a sentiment classification (Positive, Negative, Neutral) based on the score.

How It Works:
Preprocess the comment by converting it to lowercase and stripping non-alphabetic characters.
Tokenize the comment into individual words.
Calculate sentiment scores by counting occurrences of positive and negative words from predefined lists.
Classify the comment based on the sentiment score:
Positive if positive score > negative score.
Negative if negative score > positive score.
Neutral if both scores are equal.

Dependencies:
re module for regular expressions (built-in).

Use Case:
This script is ideal for quickly analyzing customer feedback or product reviews and classifying them based on sentiment to gauge overall customer satisfaction.
 
