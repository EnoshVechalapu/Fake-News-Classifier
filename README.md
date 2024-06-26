# Fake News Classifier

This repository contains a project aimed at detecting fake news using machine learning techniques. The classifier is built using Multinomial Naive Bayes and employs feature extraction methods such as TF-IDF and CountVectorizer.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Feature Extraction](#feature-extraction)
- [Model](#model)
- [Results](#results)

## Introduction

Fake news refers to misinformation or false information presented as news, often created to mislead or manipulate audiences. This project aims to build a classifier that can accurately distinguish between fake and real news articles using machine learning techniques.

## Dataset

The dataset used in this project consists of labeled news articles. Each article is labeled as either fake or real. The dataset includes a variety of news sources and covers a wide range of topics. The dataset is uploaded above as train.csv

## Feature Extraction

Two feature extraction methods are used in this project:

- **CountVectorizer**: Converts text documents to a matrix of token counts.
- **TF-IDF (Term Frequency-Inverse Document Frequency)**: Reflects the importance of a word in a document relative to a collection of documents.

## Model

The classifier is built using the Multinomial Naive Bayes algorithm, which is particularly suited for classification with discrete features (e.g., word counts for text classification).

## Results

The model achieved an accuracy of 90% on the test set. Detailed performance metrics, including confusion matrix, are provided in the results section
