# Sentiment140 Dataset Analysis


## Data Sources
[Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140): A dataset for sentiment analysis containing 1.6 million tweets.


This project involves analyzing the Sentiment140 dataset, which contains 1.6 million tweets labeled for sentiment analysis. The goal is to build a model that predicts the sentiment of tweets based on their content

## Dataset Overview

The dataset consists of the following columns:

- **target**: Sentiment of the tweet (0 for negative, 4 for positive).
- **id**: Unique identifier for each tweet.
- **date**: Date and time when the tweet was created.
- **flag**: Indicates if the tweet is flagged (not used in analysis).
- **user**: The username of the person who tweeted.
- **text**: The content of the tweet.

 ## Usage Instructions

1. **Load the dataset: Import the necessary libraries and load the dataset into a DataFrame**
2. **Preprocess the data: Clean the text data and prepare it for analysis. This may include removing links, special characters, and normalizing the text**
3. **Train the model: Use the provided code to train a sentiment analysis model on the dataset**
4. **Evaluate the model: Assess the model's performance using metrics such as accuracy, precision, recall, and F1 score**
   
## Requirements 

For text analysis, you may want to install the following libraries:

- `nltk`: Natural Language Toolkit for working with human language data.
- `textblob`: Simplified text processing for common natural language tasks.
- `scikit-learn`: For machine learning tasks related to text classification.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For visualizing text analysis results.
- `seaborn`: For enhanced visualizations.

You can install them using `pip`:

```bash
pip install nltk spacy gensim textblob scikit-learn pandas matplotlib seaborn
