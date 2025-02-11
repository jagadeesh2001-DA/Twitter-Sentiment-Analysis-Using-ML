# Twitter Sentiment Analysis Using Machine Learning

## Overview
This project performs **sentiment analysis on Twitter data** using **machine learning**. The model classifies tweets as **positive or negative**, helping to analyze public opinion on various topics.

## Features
✅ **Data Preprocessing:** Cleans and processes Twitter text data.  
✅ **Feature Extraction:** Uses TF-IDF to convert text into numerical form.  
✅ **Machine Learning Model:** Implements Logistic Regression for sentiment classification.  
✅ **Evaluation Metrics:** Assesses model performance using accuracy, precision, recall, and F1-score.  
✅ **Visualization:** Displays results through graphs and word clouds.  

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/Twitter_Sentiment_Analysis.git
   cd Twitter_Sentiment_Analysis
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the Jupyter Notebook to train and test the sentiment analysis model:
```sh
jupyter notebook Twitter_Sentiment_Analysis_Using_ML.ipynb
```

## Dataset
- **Source:** Twitter API / Pre-collected dataset
- **Labels:** 1 (Positive), 0 (Negative)
- **Processing:** Stopword removal, stemming, and tokenization

## Model Details
- **Algorithm Used:** Logistic Regression
- **Feature Extraction:** TF-IDF (Term Frequency-Inverse Document Frequency)
- **Train-Test Split:** 80%-20%

## Evaluation Metrics
📊 **Accuracy:** Measures overall correctness of predictions.  
📊 **Precision & Recall:** Evaluates model performance for each sentiment category.  
📊 **F1-Score:** Balances precision and recall.

## Results & Visualization
The project includes **visual representations of sentiment distribution** and **word clouds** to highlight frequently used words in positive and negative tweets.

## Contributing
Feel free to contribute by submitting issues or pull requests!
