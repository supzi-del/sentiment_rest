# Sentiment Analysis of Restaurant Reviews

The Sentiment Analysis of Restaurant Reviews project utilizes various machine learning algorithms to determine the sentiment of restaurant reviews. The project covers data preprocessing, model training, evaluation, and prediction.

## Data Preprocessing

The text data is preprocessed with the following steps:

1. **Remove Special Characters**: Special characters are cleaned from the text.
2. **Convert to Lowercase**: All text is converted to lowercase to ensure uniformity.
3. **Remove Stopwords**: Common stopwords are removed to focus on meaningful words.
4. **Apply Stemming**: Words are reduced to their root form using stemming.

The `CountVectorizer` is used to transform the text into numerical feature vectors suitable for machine learning models.

## Model Training

The following models are trained and evaluated:

- **Naive Bayes Classifier**
- **Logistic Regression**
- **Random Forest Classifier**

Each model is assessed based on its accuracy and other performance metrics.




