---
layout: post
title: Project Four
---
Tweet Emotions Analysis

### Introduction:

Sentiment Analysis is a technique widely used in text mining. Twitter Sentiment Analysis, therefore means, using advanced text mining techniques to analyze the sentiment of the tweets in the form of positive, negative and neutral. It is also known as Opinion Mining, is primarily for analyzing conversations, opinions, and sharing of views. <br>


### Project Workflow

* Data acquisition.
* Data preprocessing:  <br>
  Data cleaning , Tokenization , Stemming.
* Dimensionality Reduction.
* Clustering.
* Sentiments Analysis.
* Data visualization.

### Data acquisition

* The dataset is about the Twitter tweets.
* It is publicly available in the figure-eight platform.
* It contains 40,000 records. <br>

[Twitter tweets Dataset](https://www.figure-eight.com/data-for-everyone/)

### Data preprocessing

#### Data Cleaning

By Removing:  <br>

* Capital letters.
* Punctuation
* Stop words.

#### Tokenization

Is the process of tokenizing or splitting a string, text into a list of tokens. <br>

The Tokenization used is Word Tokenizer.


#### Stemming

Stemming is the process of reducing a word to its word stem.  <br>

The Stemming used is Lancaster Stemmer.


### Dimensionality Reduction

The Technique used is Non-Negative Matrix Factorization (NMF).<br>

![Image test]({{ site.url }}/images/NMF.png) <br>


### Clustering

* KMeans Clustering.
* Number of Clusters = 6.
* The number of clusters was chosen based on the result from the Silhouette Analysis. <br>

![Image test]({{ site.url }}/images/SA.png) <br>

### Sentiments Analysis

Sentiment analysis is automated process to identify positive, negative and neutral emotions from text.<br>

![Image test]({{ site.url }}/images/sentimentsAnalysis1.png) <br>

![Image test]({{ site.url }}/images/sentimentsAnalysis2.png) <br>


As shown from these visuals the positive tweets is higher compared to the others.

### Sentiments Analysis with Clustering

Sentiments Analysis for each Cluster.<br>

![Image test]({{ site.url }}/images/sentimentsAnalysis3.png) <br>

Sentiments Analysis for Second Cluster.<br>

![Image test]({{ site.url }}/images/sentimentsAnalysis4.png) <br>



### Data visualization

#### Word Cloud

A word cloud is an image made of words that together resemble a cloudy shape.<br>
The size of a word shows how important it is e.g. how often it appears in a text (its frequency).<br>

#### Word Cloud for all Tweets

![Image test]({{ site.url }}/images/WordCloud1.png) <br>

#### Word Cloud for each Cluster

![Image test]({{ site.url }}/images/AllClouds.png) <br>

#### UMap

UMap to shows the KMeans Clustering.<br>

![Image test]({{ site.url }}/images/Umap.png) <br>































