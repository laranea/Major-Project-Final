# Comparing Machine Learning Algorithms for stock prediction and stock index movement using trend deterministic data preparation techniques.

## 🚩 Table of Contents
- [Introduction](#introduction)
- [What are we doing](#what-are-we-doing)
- [How to commit](#-how-to-commit)
- [Base Research Papers](#-base-research-papers)
- [Usage](#-usage)
    - [Editor](#-editor)
    - [IDE](#-ide)
    - [Libraries](#-libraries)
    - [Dataset](#-dataset)
- [Important Links](#-important-links)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)


### Introduction
In 2014, Xinjie Di, an SCPD student from Apple Inc. submitted a paper which focused on predicting stock price trend for a company in the near future. The feature space was derived from the time series of the stock itself and was concerned with potential movement of past price. Tree algorithm was applied to feature selection and it suggests a subset of stock technical indicators are critical for predicting the stock trend.

Experiment results suggested an accuracy of more than 70% on predicting 3-10 day average price trend with SVM algorithm.

***

Another paper presented in *Expert Systems with Applications* journal under __Elsevier__ publishing company by *Jigar Patel, Sahil Shah, Priyank Thakkar, K. Kotecha* quoted as __Patel , J., et al. Predicting stock and stock price index movement using Trend Deterministic Data Preparation and machine
learning techniques. Expert Systems with Applications (2014)__ addressed the problem of predicting direction of movement of stock and stock price index for Indian Stock Markets.

The paper compares four prediction models, *Aritificial Neural Network(ANN)*, *Support Vector Machine(SVM)*, *Random Forest* and *Naive Bayes* with two approaches for input to these models.

The first approach for input data involves computation of ten technical parameters using stock trading data(open, high, low & close prices) while the second approach focuses on representing these technical parameters as trend deterministic data. Accuracy of each of the prediction models for each of the two input approaches was evaluated. Evaluation was carried out on 10 years of historical data from 2003 to 2012 of two stocks namely Reliance Industries and Infosys Ltd.

Experiment results suggested that for the first approach of input data *Random Forest* outperforms other three prediction models on overall performance. Experimental results also show that the performance of all the prediction models improve when these technical parameters are represented as trend deterministic data.


### What are we doing
Our plan is to introduce the __Long Short Term Memory(LSTM)__ and __XgBoost__ model to hopefully achieve better accuracy on overall performance. 

Also we will be comparing the performance of LSTM, and XgBoost with previously proved performance of SVM, ANN, Naive Bayes, and Random Forest by implementing these six prediction models over the dataset of various stocks.


### How to commit