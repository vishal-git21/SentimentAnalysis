# Sentiment Analysis Project

## Overview
This project is focused on sentiment analysis using machine learning techniques. It involves analyzing text reviews from various restaurants and classifying them as positive or negative based on their sentiment.

## Dataset
The dataset contains 1,000 text reviews labeled as positive or negative. It's suitable for beginners in sentiment analysis and natural language processing (NLP).

- **Columns:**
  - `Unnamed: 0`: Index or identifier for each review (ignored for analysis).
  - `sentence`: Text of the restaurant review.
  - `label`: Sentiment label (-1 for positive review, 0 for negative review).

## Features Implemented
- **Data Preprocessing:**
  - Removal of noise, punctuation, and stop words.
  - Lowercasing text and tokenization.
  - Stemming using PorterStemmer.

- **Feature Extraction:**
  - Utilization of Word2Vec embeddings for converting text into numerical vectors.

- **Models Implemented:**
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Random Forest
  - XGBoost
  - Multi-Layer Perceptron (Neural Network)

## Model Performance
- **Evaluation Metrics Used:**
  - Accuracy
  - Precision, Recall, F1-Score (for binary classification)
  
- **Best Performing Model:**
  - Neural Network (MLP) achieved the highest accuracy of 85%.

## Steps to Reproduce
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/vishal-git21/SentimentAnalysis.git
   cd SentimentAnalysis
   ```

2. **Install Dependencies:**
   Ensure you have Python and necessary libraries installed (e.g., numpy, pandas, scikit-learn).

3. **Run the Code:**
   Run the notebook 

## Directory Structure
```
SentimentAnalysis/
│
├── Beginner_Reviews_dataset                # Contains dataset 
├── SentimentAnalysis.ipynb             # Jupyter notebooks for data analysis and model training
├── README.md              # Project overview and instructions
└── Approach.txt       # Problem Approach
```

## Author
- **Vishal** - [GitHub](https://github.com/vishal-git21)
