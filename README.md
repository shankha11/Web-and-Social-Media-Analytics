# Web and Social Media Analytics

This project analyzes web and social media data to understand customer sentiment and behavior. It involves data cleaning, feature extraction, model building, and visualization using machine learning techniques.

## Project Overview

The goal of this project is to perform sentiment analysis on social media reviews using various machine learning models, including Naive Bayes, Random Forest, and XGBoost. The insights derived from this analysis can help businesses understand customer opinions and improve their services.

## Dataset

The dataset used for this project is sourced from social media reviews related to Hotstar. It contains the following fields:

- `Lower_Case_Reviews`: The review text in lowercase.
- `DataSource`: The source of the review.
- `Sentiment_Manual`: The manually labeled sentiment (Positive, Negative, Neutral).

## Model Performance

The following metrics summarize the performance of the different machine learning models used in this project:

### Naive Bayes Classifier
- **Training Accuracy:** 88.02%
- **Test Accuracy:** 71.61%

### Random Forest Classifier
- **Training Accuracy:** 99.03%
- **Test Accuracy:** 70.32%

### XGBoost Classifier (using Bag of Words)
- **Training Accuracy:** 83.91%
- **Test Accuracy:** 71.81%

### XGBoost Classifier (using TF-IDF)
- **Training Accuracy:** 88.17%
- **Test Accuracy:** 71.17%

### Word Cloud Analysis
- **Positive Reviews:** The word cloud visualization highlights the most common words in positive reviews.
![Screenshot (1829)](https://github.com/user-attachments/assets/872b9aee-6039-4d21-ba4b-214e9fcf0373)


- **Negative Reviews:** The word cloud visualization shows the prevalent terms in negative reviews.
![Screenshot (1830)](https://github.com/user-attachments/assets/c2cff03a-4338-4aea-990c-b87713f5fdf2)

   
- **Neutral Reviews:** The word cloud provides insight into the language used in neutral reviews.
![Screenshot (1831)](https://github.com/user-attachments/assets/f20bdb4d-f6a4-4543-8db7-a71ac8568bcc)

  
These results reflect the accuracy and effectiveness of each model in classifying sentiment in social media reviews. The percentages represent the accuracy on the test dataset, providing an indication of how well the models generalize to unseen data.

## Project Structure

- `datasets/`: Contains the dataset used in the analysis.
- `notebooks/`: Jupyter Notebook with full analysis and code, including data cleaning, feature extraction, model building, and visualization.
- `README.md`: Project documentation.
