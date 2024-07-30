# Amazon Product Reviews Extraction and Sentiment Analysis

## Overview
This project aims to implement advanced machine learning techniques to gain a better understanding of complex language patterns in Amazon product reviews, leading to more accurate predictions. The project involved extracting, cleaning, and analyzing a dataset of over 20,000 Amazon product reviews, performing sentiment analysis focused on specific aspects of the products, and achieving a 20% increase in model accuracy through hyperparameter tuning.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Sentiment Analysis](#sentiment-analysis)
- [Model Training](#model-training)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Sentiment analysis of product reviews is crucial for understanding customer satisfaction and improving product quality. This project utilizes machine learning techniques to perform sentiment analysis on Amazon product reviews, focusing on specific aspects of the products. By analyzing the sentiment expressed in reviews, we can provide valuable insights to both customers and sellers.

## Dataset
The dataset used in this project consists of over 100,000 Amazon product reviews. Each review includes various features such as the review text, rating, and product information. The dataset was obtained using a Python script developed with Selenium to extract the necessary reviews and fields.

## Data Preprocessing
Data preprocessing steps included:
- Removing duplicates and missing values.
- Normalizing text (lowercasing, removing punctuation, etc.).
- Tokenizing and stemming/lemmatizing words.
- Converting text to numerical representations using techniques like TF-IDF or word embeddings.

## Sentiment Analysis
The sentiment analysis focused on identifying the sentiment expressed in reviews regarding specific aspects of the products, such as quality, price, and usability. This involved:
- Annotating the dataset with aspect-based sentiment labels.
- Training models to classify sentiment for each aspect.

## Model Training
Various machine learning models were trained to perform sentiment analysis, including:
- Logistic Regression
- Support Vector Machines (SVM)
- Random Forest
- Deep Learning models (e.g., LSTM, BERT)

## Hyperparameter Tuning
Hyperparameter tuning was performed to optimize the performance of the models. Techniques used included:
- Grid Search
- Random Search
- Bayesian Optimization

Through hyperparameter tuning, we achieved a 20% increase in model accuracy.

## Results
The final models demonstrated significant improvements in accurately predicting sentiment for various aspects of the products. The best model achieved an accuracy of [accuracy percentage] on the test set.

## Installation
To install the necessary dependencies, run the following command:
```bash
pip install -r requirements.txt
