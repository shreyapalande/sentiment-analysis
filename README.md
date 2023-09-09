# Sentiment Analysis
Performing sentiment analysis on customer reviews involves using machine learning (ML) algorithms to automatically determine the sentiment or emotional tone expressed in the reviews.

## Data Collection: 
Dataset is taken from kaggle. Each entry is labeled as positive or negative.
Link : https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews

## Data Preprocessing:
Text Cleaning: Remove special characters, symbols, and irrelevant information from the reviews.
Tokenization: Spliting the text into individual words or tokens.
Stopword Removal: Eliminate common words like "and," "the," and "is" that don't carry significant sentiment.
Stemming or Lemmatization: Reduce words to their base or root form to standardize variations (e.g., "running" becomes "run").

## Feature Extraction:
Bag of Words (BoW): Convert text data into numerical features by creating a matrix where each row corresponds to a review and each column represents a unique word in the dataset. The values indicate the word's frequency in each review.
TF-IDF (Term Frequency-Inverse Document Frequency): Similar to BoW but considers the importance of words in the entire dataset, giving higher weight to rare words.

## Model Selection:
Using an ML algorithm for text classification and sentiment analysis. Algorithms used in this notebook include :
1. Naive Bayes
2. Logistic Regression
3. Support Vector Machines (SVM)
4. Random Forest
5. Neural Networks (RNN)

## Training the Model:
Spliting the dataset into training and testing sets to evaluate model performance.
Train the selected ML algorithm on the training data.

## Model Evaluation:
Use evaluation metrics such as accuracy, precision, recall, and F1-score to assess the model's performance on the test data.

## Sentiment Prediction:
Once the model is trained and validated, you can use it to predict the sentiment of new customer reviews.
The model will classify each review as positive or negative based on the learned patterns in the data.
