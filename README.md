
# Sentiment Analysis on Intel Core Desktop Processor Gen 12 Reviews

This project performs sentiment analysis on user reviews of the Intel Core desktop processor generation 12. Reviews are scraped from Amazon and Flipkart using BeautifulSoup, cleaned to remove missing and unwanted data, and then used to train a sentiment analysis model. The code is written in Google Colab.

## Table of Contents

- [Overview](#overview)
- [Data Collection](#data-collection)
- [Data Cleaning](#data-cleaning)
- [Model Training](#model-training)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to analyze user sentiments regarding the Intel Core desktop processor generation 12 by leveraging reviews from major e-commerce platforms. This involves:
1. Scraping reviews from Amazon and Flipkart.
2. Cleaning and preprocessing the data.
3. Training a sentiment analysis model on the cleaned data.
4. Evaluating the model's performance.

## Data Collection

Reviews are scraped using the BeautifulSoup library from:
- **Amazon**
- **Flipkart**

## Data Cleaning

The scraped data undergoes several preprocessing steps, including:
- Removing missing values
- Filtering out unwanted data (e.g., non-English reviews, irrelevant content)

The data cleaning scripts are available in the `cleaning/` directory.

## Model Training

The cleaned data is used to train a sentiment analysis model. The model development includes:
- Data splitting (training and testing sets)
- Feature extraction
- Model training
- Performance evaluation
