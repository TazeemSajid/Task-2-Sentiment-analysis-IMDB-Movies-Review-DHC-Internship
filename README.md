# Task-2-Sentiment-analysis-IMDB-Movies-Review-DHC-Internship
Task 2: Sentiment Analysis on IMDB Reviews
**📌 Project Description**

This project implements a sentiment analysis model on a reduced IMDB reviews dataset. Instead of using the original 50,000 reviews, a smaller dataset of 1,000 reviews (balanced with 500 positive and 500 negative) was used for simplicity and faster execution.

The goal is to classify each movie review as positive or negative using a Logistic Regression model.

**📊 Steps Performed**

Dataset

Used imdb_reviews_1000.csv with 2 columns:

review → text of the review

sentiment → label (positive / negative)

1:Preprocessing

2:Converted text to lowercase.

3:Removed HTML tags, punctuation, and numbers.

4:Feature Engineering

5:Converted text into numerical format using CountVectorizer (Bag of Words).

6:Model Training & Evaluation

7:Trained a Logistic Regression model.

8:Evaluated accuracy on a test set (20% of data).

9:User Input Prediction

At the end of the script, users can type their own review and get a predicted sentiment.

**📂 Files**

task2_sentiment_analysis_imdb_reviews.py → Python script for training, evaluation, and prediction.

imdb_reviews_1000.csv → Dataset used in this project.

**▶️ How to Run**

**Install dependencies:**

pip install pandas scikit-learn


**Place both files in the same folder:**

Sentiment-Analysis/
│── task2_sentiment_analysis_imdb_reviews.py
│── imdb_reviews_1000.csv


**Run the script:**

python task2_sentiment_analysis_imdb_reviews.py


Enter a review when prompted to get a prediction.
