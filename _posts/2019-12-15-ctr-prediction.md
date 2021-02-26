---
title: "Click-Through Rate Prediction"
date: 2019-12-15T15:34:30-04:00
categories:
  - UC Berkeley Academic Project
tags:
  - Massively Parallel Processing
  - Apache Spark
  - Docker
  - Factorization Machine
---
In this project we attempted the [Kaggle Display Advertising Challenge in 2014](https://www.kaggle.com/c/criteo-display-ad-challenge) which is to train a model with 10GB of web traffic data to predict click-through rate (CTR, percent of ads clicked).

## Description
Inspired by the [winning team](https://www.kaggle.com/c/criteo-display-ad-challenge/discussion/10555)'s approach, we explained the concept of field-aware fectorization machine (FFM) and sought to build our own homegrown FFM model with PySpark's RDD API. The primary goal is to beat a baseline model defined by measuring the overall click-through rate. A secondary goal is to match the model performance of competition-winning models.

## Techniques
* factorization machine
* logistic regression
* massively parallel processing

## Tools
* Apache Spark
* Parquet
* Docker
* GCP
* Pandas
* Matplotlib

## More Information
More information can be found at the following links:

* [Project Notebook](https://github.com/erikhou45/ctr-prediction/blob/main/final_project.ipynb)
* [Project Repository](https://github.com/erikhou45/ctr-prediction)
