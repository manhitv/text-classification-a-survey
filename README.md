# Text Classification - A survey with hands-on examples

## Introduction

In this repository, I have surveyed approaches to a typical Text Classification problem and demonstrated through hands-on examples. Those are some opinions on text processing methods, text classfication algorithms and some utilities when working with text data.

## Table of Contents

### Text and Document Feature Extraction
**1. Introduction to data preprocessing**

- *Data cleaning*
- *Data wrangling*
- *Data reduction or instance/feature selection and extraction*

**2. Text Cleaning and Pre-processing**

- *Must Do*:
    + Noise removal
    + Lowercasing (can be task dependent in some cases)
- *Should Do*:
    + Simple normalization – (e.g. standardize near identical words)
- *Task Dependent*:
    + Advanced normalization (e.g. addressing out-of-vocabulary words)
    + Stop-word removal
    + Stemming / Lemmatization
    + Text enrichment / Augmentation
- *Additional considerations*:
    + Handling large documents and large collections of text documents.
    + Extracting text from markup like HTML, PDF or other structured document formats.
    + Trans-literation of characters from other languages into English.
    + Handling of domain specific words, phrases and acronyms.
    
    There are some techniques that help to deal with these problems such as *Tokenization*, *Stop words*, *Capitalization*, *Slangs and Abbreviations*, *Spelling Correction*, *Stemming*, *Lemmatization*.

**3. Feature Extraction 1 - Word Embedding**

  * *Word2Vec*   
  * *Global Vectors for Word Representation (GloVe)*
  * *Contextualized Word Representations*    
  * *FastText*

**4. Feature Extraction 2 - Weighted Words**

**5. Comparison of Feature Extraction Techniques**

----
### Text Classification Techniques 
**1. Non-neural network**
  * *Linear models (RidgeClassifier, SGDClassifier)*
  * *Naive Bayes Classifier*
  * *Support Vector Machine (LinearSVC)*
  * *Random Forest (Bagging)*
  * *GradientBoosting (Boosting)*

**2. Neural network (Deep Learning)**
   * *Deep Neural Networks*
   * *Recurrent Neural Networks (RNN): Gated Recurrent Unit (GRU) / Long Short-Term Memory (LSTM)*
   * *Convolutional Neural Networks (CNN)*
   * *Recurrent Convolutional Neural Networks (RCNN)*
   * *Transformers*
   * *Some pretrained models*

**3. Comparison Text Classification Algorithms**

   * *Non-neural network*
   * *Deep Learning*
----
### Some applications

* *Information Retrieval*
* *Information Filtering*
* *Sentiment Analysis*
* *Recommender Systems*
* *Knowledge Management*
* *Document Summarization*
----