# Spam Email Classifier
A basic machine learning model that classifies emails into two categories- spam and not-spam (or ham) based on the content of the email.
## Dataset
This project uses the 'Spam Emails' dataset from Kaggle - https://www.kaggle.com/datasets/abdallahwagih/spam-emails
## Data Preprocessing
Used TF-IDF vectorization to convert textual data into numerical data for further processing.
## Model 
To classify the data into the two categories, Naive Bayes classification was used due to its higher efficiency with large datasets especially textual data.
## Usage
To use the spam email classifier:

1. Preprocess the email data to extract features and prepare it for training.
2. Train the Naive Bayes classifier using the preprocessed email data.
3. Evaluate the performance of the trained classifier using metrics such as accuracy, precision, recall, and F1-score.

## Results
Accuracy: 0.95
