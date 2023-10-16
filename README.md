# Sentimental Analysis of Pharmaceutical Reviews

### Overview
<p align="justify">This project performs sentiment analysis on pharmaceutical reviews. It classifies reviews into different sentiment categories and provides insights into the sentiment of the reviews. It also predicts the sentiment of the review, the condition being reviewed, and the rating.

### Table of Contents
- Data Acquisition
- Data Preprocessing
- Text Preprocessing (Natural Language Processing)
- Machine Learning
  - Sentiment Prediction
  - Condition Prediction
  - Rating Prediction
- Sentiment Analysis Using LSTM

### Data Acquisition
- The project begins by importing the necessary libraries for data manipulation and analysis.
- It loads the training and testing data from CSV files, `train_data.csv` and `test_data.csv`.

### Data Preprocessing
- Checks the shape of the training and testing datasets.
- Merges the training and testing data for further analysis.
- Performs data cleaning, handling null values, and transforming date columns into year, month, and day.

### Text Preprocessing (Natural Language Processing)
- Imports libraries for text preprocessing.
- Performs text cleaning by converting text to lowercase, removing special characters, and non-ASCII characters.
- Removes stopwords and applies stemming to the reviews.

### Machine Learning
- The machine learning section of the project is divided into three parts: Sentiment Prediction, Condition Prediction, and Rating Prediction.
- <p align="justify">It uses various machine learning algorithms such as Logistic Regression, Decision Tree, Random Forest, XGBoost for classification tasks and Linear Regression, Decision Tree, Random Forest, XGBoost for regression tasks.
- It evaluates the performance of each algorithm using cross-validation, grid search, and relevant evaluation metrics.

### Sentiment Analysis Using LSTM
- Utilizes deep learning techniques with LSTM to perform sentiment analysis.
- Preprocesses text data, tokenizes and pads sequences.
- Builds an LSTM model for sentiment classification.
- Trains and evaluates the model's performance using classification metrics.
