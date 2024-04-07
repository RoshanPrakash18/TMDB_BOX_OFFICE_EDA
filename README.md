<div align="center">
  <h1>🎬 Box Office Revenue Prediction</h1>
  <p><i>An case study by Roshan Prakash</i></p>
</div>

## 📝 Project Overview

Welcome to the **Box Office Revenue Prediction** project repository! This project aims to analyze and predict box office revenue for movies using data from the TMDB (The Movie Database) dataset. We explore various factors influencing movie revenue and build a predictive model to estimate future box office performance.

## 🗂️ Table of Contents

1. [Project Overview](#-project-overview)
2. [Data Preparation](#-data-preparation)
3. [Exploratory Data Analysis](#-exploratory-data-analysis)
4. [Feature Engineering and Modeling](#-feature-engineering-and-modeling)
5. [Conclusion and Future Work](#-conclusion-and-future-work)
6. [Citation](#-citation)

## 🛠️ Data Preparation

We load the dataset by downloading the train.csv and test.csv from [Kaggle](https://www.kaggle.com/competitions/tmdb-box-office-prediction). Additionally, we add log-transformed columns to handle skewness in the target variable.

## 🔍 Exploratory Data Analysis

### 📊 Target Variable Distribution

We visualize the distribution of the target variable (revenue) and its log-transformed counterpart.

### 💰 Revenue vs. Budget

We explore the relationship between movie revenue and budget, both in their original and log-transformed forms.

### 🌐 Impact of Homepage and Language

We analyze the impact of having a homepage and the original language of the movie on its revenue.

### 🎨 Word Clouds for Titles and Overviews

We create word clouds to visualize the most frequent words in movie titles and overviews.

### 📝 Impact of Overview Text on Revenue

We use TF-IDF vectorization to analyze the impact of movie overview text on revenue prediction.

### 📈 Revenue Trends Over Time

We examine the trend in movie revenue over the years to identify any temporal patterns.

## 🧰 Feature Engineering and Modeling

We train a baseline linear regression model using TF-IDF features extracted from movie overviews to predict log revenue. We evaluate the model's performance using mean squared error (MSE) and R-squared (R^2) metrics.

## 🚀 Conclusion and Future Work

This project provides valuable insights into the factors influencing box office revenue for movies.

## 📚 Citation

This project is based on the TMDB Box Office Prediction competition hosted on Kaggle in 2019. For more details, please refer to the [competition page](https://www.kaggle.com/competitions/tmdb-box-office-prediction).
