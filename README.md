# Language Detection using NLP

## Description
This project implements a **language detection system** that predicts the language of a given text using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

The model supports **17 languages**.

## Supported Languages
German, English, Arabic, Danish, Spanish, French, Greek, Hindi, Italian, Kannada, Malayalam, Dutch, Portuguese, Russian, Swedish, Tamil, Turkish.

## Dataset
- File: `language_detection.csv`
- Size: 10,267 text samples
- Columns:
  - `Text`: written text
  - `Language`: language label  
- Source: Wikipedia (web scraping)

## Methodology
1. Data exploration
2. Label encoding of languages
3. Text preprocessing (remove symbols & digits)
4. Text vectorization using **Bag of Words**
5. Train/test split (80% / 20%)
6. Model training using **Multinomial Naive Bayes**
7. Evaluation with accuracy and confusion matrix

## Evaluation
The model achieves high accuracy, especially for languages with distinct alphabets.  
Performance is measured using **accuracy** and a **confusion matrix**.

## Prediction
The trained model can predict the language of new, unseen texts.

## Technologies
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
