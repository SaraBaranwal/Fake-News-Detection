# Fake News Detection Using Machine Learning

This project uses machine learning techniques to classify news articles as **Real** or **Fake**.

The project uses TF-IDF vectorization to convert news text into numerical features and compares multiple machine learning models.

## Features

- News dataset exploration and preprocessing
- Real and Fake news distribution analysis
- TF-IDF text vectorization
- Multiple machine learning models
- Model performance comparison
- Classification reports
- Confusion matrices
- Prediction on user-provided news text

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning Models

The following models were used and compared:

1. Passive Aggressive Classifier
2. Logistic Regression
3. Linear Support Vector Machine (SVM)

## How It Works

1. Load the news dataset
2. Explore and preprocess the data
3. Split the data into training and testing sets
4. Convert news text into numerical features using TF-IDF
5. Train multiple machine learning models
6. Evaluate each model using accuracy and classification metrics
7. Compare model performance
8. Predict whether new news text is Real or Fake

## Project Structure

```text
fake-news-detection-ml/
│
├── FakeNewsDetection.ipynb
└── README.md
