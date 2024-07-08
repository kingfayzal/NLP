# NLP Exploration

## Overview
This project demonstrates various Natural Language Processing (NLP) techniques using Python libraries such as spaCy and NLTK. The project includes text preprocessing (stemming and lemmatizing), visualization with word clouds, and sentiment analysis using the IMDB movie reviews dataset.

## Table of Contents
1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Text Preprocessing](#text-preprocessing)
4. [Word Cloud Generation](#word-cloud-generation)
5. [Sentiment Analysis](#sentiment-analysis)
6. [Results](#results)
7. [Conclusion](#conclusion)

## Introduction
The main objectives of this project are:
- To demonstrate text preprocessing techniques including stemming and lemmatization.
- To visualize the processed text data using word clouds.
- To perform sentiment analysis on the IMDB movie reviews dataset.

## Requirements
- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries: pandas, spaCy, matplotlib, nltk, wordcloud


## Text Preprocessing

We define a function stem_and_lemmatize_sentences to process sentences using spaCy. This function performs the following tasks:

Loads the spaCy English model.
Processes each sentence to extract original words, lemmatized words, and stemmed words.
Stores the results in a DataFrame.

## Word Cloud Generation
We generate word clouds to visualize the lemmatized text data. This involves concatenating all lemmatized words into a single string and using the WordCloud class from the wordcloud library to create the visualization.

## Sentiment Analysis
The project utilizes the IMDB movie reviews dataset from the NLTK library to perform sentiment analysis. The dataset is split into positive and negative reviews, which are then combined into a single DataFrame.

## Results
The project outputs a DataFrame containing the original, lemmatized, and stemmed versions of each word in the sentences. Additionally, word clouds are generated to visualize the text data, and the sentiment analysis results are displayed.

## Conclusion
This project showcases fundamental NLP techniques including text preprocessing, visualization, and sentiment analysis. It provides a comprehensive example of how to preprocess text data and extract meaningful insights using Python libraries.

For more details, refer to the complete code in the notebook.
