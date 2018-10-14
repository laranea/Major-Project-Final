# Comparing Machine Learning Algorithms for stock prediction and stock index movement using trend deterministic data preparation techniques.

## If you're into presentations rather than readme files, we'd suggest you to check out the project [presentation](https://github.com/samacker77/Major-Project-Final/blob/SamarSrivastava/Presentations/01%20-%20Presentation%2015%20Oct%202018.pptx)

## 🚩 Table of Contents
- [Introduction](#-introduction)
- [What are we doing](#what-are-we-doing)
- [How to commit](#-how-to-commit)
- [Base Research Papers](#-base-research-papers)
- [Technology Stack](#-technology-stack)
	- [Programming Language](#programming-language)
    - [Editor](#editor)
    - [IDE](#ide)
    - [Libraries](#libraries)
    - [Dataset](#dataset)
- [Further Reading](#further-reading)
- [Screenshots](#-screenshots)
- [Team](#-team)
- [Mentor](#-mentor)
- [Guidelines](#guidelines)
- [License](#-license)


## 💡 Introduction
In 2014, Xinjie Di, an SCPD student from Apple Inc. submitted a paper which focused on predicting stock price trend for a company in the near future. The feature space was derived from the time series of the stock itself and was concerned with potential movement of past price. Tree algorithm was applied to feature selection and it suggests a subset of stock technical indicators are critical for predicting the stock trend.

Experiment results suggested an accuracy of more than 70% on predicting 3-10 day average price trend with SVM algorithm.

***

Another paper presented in *Expert Systems with Applications* journal under __Elsevier__ publishing company by *Jigar Patel, Sahil Shah, Priyank Thakkar, K. Kotecha* quoted as __Patel , J., et al. Predicting stock and stock price index movement using Trend Deterministic Data Preparation and machine
learning techniques. Expert Systems with Applications (2014)__ addressed the problem of predicting direction of movement of stock and stock price index for Indian Stock Markets.

The paper compares four prediction models, *Aritificial Neural Network(ANN)*, *Support Vector Machine(SVM)*, *Random Forest* and *Naive Bayes* with two approaches for input to these models.

The first approach for input data involves computation of ten technical parameters using stock trading data(open, high, low & close prices) while the second approach focuses on representing these technical parameters as trend deterministic data. Accuracy of each of the prediction models for each of the two input approaches was evaluated. Evaluation was carried out on 10 years of historical data from 2003 to 2012 of two stocks namely Reliance Industries and Infosys Ltd.

Experiment results suggested that for the first approach of input data *Random Forest* outperforms other three prediction models on overall performance. Experimental results also show that the performance of all the prediction models improve when these technical parameters are represented as trend deterministic data.

***

## 🎓 What are we doing

In our initial research we found out that efficiency in predicting stock price movements and their trends maybe improved if the prediction model could “remember” the historical movement of the stocks.

General prediction models that are used in the previously described research papers like Naive Bayes, Support Vector Machines, Random Forest, etc., can only take in consideration the most recent previous input received to the model.

Our motive is to implement the Long Short Term Memory networks in the prediction on stock price movements and their trends, as LSTM networks have  internal contextual state cells that act as long-term or short-term memory cells.

The output of the LSTM network is modulated by the state of these cells. This is a very important property when we need the prediction of the neural network to depend on the historical context of inputs, rather than only on the very last input.

***


## 📙 Base Research Papers

1. [Xinjie Di, Stock Trend Prediction with Technical Indicators using SVM](https://drive.google.com/file/d/16UR4ixLFIvLkimLu5G3Mc_jr3sDVa-0e/view?usp=sharing)

2. [Jigar Patel, Sahil Shah, Priyank Thakkar, K. Kotecha, Predicting stock and stock price index movement using Trend Deterministic Data Preparation and machine learning techniques](https://drive.google.com/file/d/1PJA8xqVKFXLMcQmhvBWS7Huw6ab-AX6h/view?usp=sharing)

***

## 💻 Technology Stack

* ### Programming Language

Python3.6 is the programming language used in the experiment.

* ### Editor

For code editing creating files we are using the following editors:
* [Visual Studio Code](https://code.visualstudio.com/)
* [Sublime Text 3](https://www.sublimetext.com/3)

* ### IDE

For development, training, deployment of the models, we are using [Jupyter Notebook](http://jupyter.org/) along with [Anaconda](https://www.anaconda.com/) Integrated Development Environment.

* ### Libraries

* Numpy
* Pandas
* scikit-learn
* matplotlib
* keras
* tensorflow

***

## 📚 Further Reading

* [Naive Bayes](https://www.analyticsvidhya.com/blog/2017/09/naive-bayes-explained/)
* [Support Vector Machine](https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/)
* [Random Forest](https://www.analyticsvidhya.com/blog/2016/04/complete-tutorial-tree-based-modeling-scratch-in-python/)
* [Artificial Neural Network](https://www.analyticsvidhya.com/blog/2014/10/introduction-neural-network-simplified/)
* [XGBoost](https://machinelearningmastery.com/gentle-introduction-xgboost-applied-machine-learning/)
* [Long Short Term Memory](https://www.analyticsvidhya.com/blog/2017/12/fundamentals-of-deep-learning-introduction-to-lstm/)


***

## 🐾 Screenshots




***





## 🚀 Results









***




## 👫 Team
1. [Samar Srivastava](http://samarsrivastava.me)
2. [Mohak Kulshrestha](https://github.com/MohakKul)
3. [Saurabh Arya](http://saurabharya.me)
4. Kashvi Agarwal


***

## 🤯 Mentor

### Mr. Munish Khanna, Head Of Department, CSE, HCST, Farah

***

## Guidelines
Please follow the following [guidelines](https://github.com/samacker77/Major-Project-Final/blob/SamarSrivastava/Commit%20Guidelines.md) in order to commit to the repository.

***


## 📜 License
This software is licensed under the [GNU General Public License v3.0](https://github.com/samacker77/Major-Project-Final/blob/master/LICENSE.md) 