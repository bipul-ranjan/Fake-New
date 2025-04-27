# Fake News Detection

## Objective

The objective of this assignment is to develop a Semantic Classification model. The Word2Vec method is used to extract the semantic relations from the text and develop a basic understanding of how to train supervised models to categorize text based on its meaning, rather than just syntax. This technique is explored in situations where understanding textual meaning plays a critical role in making accurate and efficient decisions.

## Business Objective

The spread of fake news has become a significant challenge in today’s digital world. With the massive volume of news articles published daily, it’s becoming harder to distinguish between credible and misleading information. This creates a need for systems that can automatically classify news articles as true or fake, helping to reduce misinformation and protect public trust.

In this assignment, a Semantic Classification model is developed that uses the Word2Vec method to detect recurring patterns and themes in news articles. Using supervised learning models, the goal is to build a system that classifies news articles as either fake or true.

## Pipelines Performed

The following tasks were performed to complete the assignment:

1.  Data Preparation
2.  Text Preprocessing
3.  Train Validation Split
4.  EDA on Training Data
5.  EDA on Validation Data \[Optional]
6.  Feature Extraction
7.  Model Training and Evaluation

## Data Dictionary

For this assignment, two datasets, `True.csv` and `Fake.csv`, are used. Both datasets contain three columns:

* title of the news article
* text of the news article
* date of article publication

`True.csv` dataset includes 21,417 true news, while the `Fake.csv` dataset comprises 23,502 fake news.

## Installation

The following libraries are required to run this notebook:

```bash
pip install numpy==1.26.4 pandas==2.2.2 nltk==3.9.1 spacy==3.7.5 scikit-learn==1.4.1 matplotlib==3.8.3 seaborn==0.13.2 WordCloud
