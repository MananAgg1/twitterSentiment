# Twitter Sentiment Analysis using Apache Spark MLlib

This project performs sentiment analysis on a Twitter dataset using Apache Spark's MLlib. It leverages the power of distributed computing to preprocess, analyze, and classify tweets based on their sentiment.

## 🔍 Project Overview

- **Objective:** Classify tweets into sentiment categories using Logistic Regression in Apache Spark.
- **Dataset:** Twitter Training Data (CSV format).
- **Tools & Libraries:** Apache Spark, PySpark, Spark MLlib, Matplotlib, Seaborn.

## 🧱 Project Structure

1. **Setup & Configuration**
   - Spark and JDK installation
   - Environment variable setup
   - SparkSession initialization

2. **Data Preprocessing**
   - Cleaning tweet text (lowercasing, removing special characters)
   - Handling null values
   - Mapping sentiment to binary labels (`0` for Negative, `1` for Neutral/Positive)

3. **Distributed Storage & SQL Queries**
   - Registered Spark SQL table
   - Stored cleaned data in Parquet format
   - Performed analytical queries for sentiment distribution, tweet length, common words, etc.

4. **Model Training & Evaluation**
   - Text vectorization using TF-IDF
   - Logistic Regression model training
   - Accuracy, Precision, Recall, and F1-score evaluation
   - Confusion Matrix, ROC Curve, and Precision-Recall Curve visualizations

## ✅ Results

- **Model Accuracy:** ~X.XX (replace with actual score)
- **Precision / Recall / F1-Score:** Reported using evaluation metrics
- **Visual Insights:** Included bar charts, pie charts, histograms, boxplots, and word frequency graphs

## ⚠️ Limitations

- Sentiment is simplified to binary (Neutral and Positive merged)
- Only one classification model used (Logistic Regression)
- Basic text preprocessing (no lemmatization or advanced NLP)

## 🔮 Future Enhancements

- Enable **multi-class classification** (Negative / Neutral / Positive)
- Explore **deep learning models** (LSTM, BERT)
- Build a **real-time sentiment dashboard** using streaming data

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/twitter-sentiment-analysis-spark.git
   cd twitter-sentiment-analysis-spark
