# Personality Prediction Using Text (MBTI Classifier)

MBTI stands for Myers-Briggs Type Indicator — a personality classification system based on Carl Jung’s theory of psychological types.
It categorizes people into 16 personality types based on four key dimensions:

Introversion (I) vs. Extraversion (E) – How you get your energy (from alone time vs. social interaction)

Sensing (S) vs. Intuition (N) – How you process information (facts/details vs. big picture/ideas)

Thinking (T) vs. Feeling (F) – How you make decisions (logic vs. values/empathy)

Judging (J) vs. Perceiving (P) – How you interact with the world (structured/planned vs. flexible/adaptable)


This project uses machine learning and natural language processing (NLP) techniques to predict a person's MBTI (Myers-Briggs Type Indicator) personality type based on their written text.

## Project Overview
The goal of this project is to classify users into one of the 16 MBTI personality types using a dataset of personal posts. Each post is labeled with one of the MBTI types, such as INFP, ENTP, or ISTJ.

## Key Features
Text Preprocessing: Includes cleaning, tokenization, lemmatization, and stopword removal.

TF-IDF Vectorization: Converts processed text into numerical features.

Multiclass Classification: Uses machine learning models like Logistic Regression, Random Forest, and SVM to predict MBTI types.

Model Evaluation: Includes accuracy, precision, recall, and confusion matrix to assess performance.

## Tools & Libraries
Python

pandas, NumPy

scikit-learn

NLTK / spaCy (for NLP)

Matplotlib / Seaborn (for visualization)

## Results
Achieved competitive accuracy on test data. The model was able to reasonably distinguish between different MBTI types based on writing style and word choice.

## Learnings
Applied NLP preprocessing techniques to a real-world dataset

Understood challenges in multi-class text classification

Gained insight into how language reflects personality

