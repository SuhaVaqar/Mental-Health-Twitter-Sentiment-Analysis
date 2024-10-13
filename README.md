# Mental Health Twitter Sentiment Analysis

This project analyzes the sentiment of Twitter posts related to mental health using machine learning models like Decision Trees, Random Forest, KNN, and Naive Bayes. The dataset is preprocessed to clean the text, and the sentiment is classified as either positive or negative.

## Steps:
1. **Data Preprocessing**: 
   - Converted text to lowercase
   - Removed numbers, punctuation, and stopwords
   - Applied lemmatization

2. **Sentiment Analysis**: 
   - Used `TextBlob` to calculate polarity
   - Classified as positive or negative sentiment

3. **Machine Learning Models**: 
   - Trained and tested on Decision Tree, Random Forest, KNN, and Naive Bayes classifiers
   - Accuracy and confusion matrix were evaluated

## Requirements:
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `nltk`, `sklearn`, `TextBlob`


