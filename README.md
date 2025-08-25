# Email Spam Classifier 

Determines if an email is spam or not using a machine learning model.  
Python, pandas, scikit-learn, and TF-IDF vectorisation are used in the model's construction.

## How to use

1. Open in Colab or Jupyter
2. Ensure mail_data.csv is contained in the same folder
3. Run all cells to train and test the model

## Features

- Reads email data from a CSV file
- Preprocesses text and labels
- Uses TF-IDF to turn text into numerical features
- Trains a classifier for logistic regression
- Assesses accuracy on test data that hasn't been seen
