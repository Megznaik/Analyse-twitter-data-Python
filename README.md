# Sentiment Analysis and Hashtag Exploration on Twitter Data using Python

This Python script performs sentiment analysis and hashtag exploration on a Twitter dataset using Pandas, Regular Expressions, TextBlob, and Matplotlib. The script extracts tweets from a CSV file, performs various text-processing tasks, calculates sentiment scores, and visualizes the results.

## Dependencies
Python 3.x 

Pandas

Matplotlib

TextBlob

## Description
The script performs the following tasks:

**Data Loading:** Loads Twitter data from a CSV file into a Pandas DataFrame.

**Text Processing:** 
Removes unnecessary columns (e.g., user_name, location).
Extracts hashtags and mentions from tweets using regular expressions.
Counts the number of hashtags and mentions.
Analyzes sentiment using TextBlob and assigns sentiment levels (positive, negative, neutral) to each tweet.

**Hashtag Exploration:**
Counts the occurrences of each hashtag.
Identifies the top five most used hashtags.
Visualizes the frequency of the top hashtags using a bar chart.

**Sentiment Analysis:**
Visualizes the distribution of sentiment levels using a pie chart.

## Results
The script generates visualizations illustrating the sentiment distribution and the most frequently used hashtags in the Twitter dataset.

## Installation
To use this code, you can clone this repository using Git:
git clone https://github.com/Megznaik/Analyse-twitter-data-Python.git

## Contributing
Contributions are welcome! If you find any issues or improvements, you can open an issue or create a pull request.
