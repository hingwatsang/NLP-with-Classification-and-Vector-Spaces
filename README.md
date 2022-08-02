# NLP-with-Classification-and-Vector-Spaces

In this course, I   

a) Perform sentiment analysis of tweets using logistic regression and then naïve Bayes, <br>
b) Use vector space models to discover relationships between words and use PCA to reduce the dimensionality of the vector space and visualize those relationships, and<br>
c) Write a simple English to French translation algorithm using pre-computed word embeddings and locality-sensitive hashing to relate words via approximate k-nearest neighbor search.



## Assignment 1: Logistic Regression
I leanrt learn about logistic regression. Concretely, I implemented logistic regression for sentiment analysis on tweets. Given a tweet, I decided if it has a positive sentiment or a negative one. Specifically, I

<li>Learn how to extract features for logistic regression given some text</li>
<li>Implement logistic regression from scratch</li>
<li>Apply logistic regression on a natural language processing task</li>
<li>Test using your logistic regression</li>
<li>Perform error analysis</li>


## Assignment 2: Naive Bayes
I learnt about Naive Bayes. Concretely, I used Naive Bayes for sentiment analysis on tweets. Given a tweet, I decided if it has a positive sentiment or a negative one. Specifically, I

<li>Train a naive bayes model on a sentiment analysis task</li>
<li>Test using your model</li>
<li>Compute ratios of positive words to negative words</li>
<li>Do some error analysis</li>
<li>Predict on your own tweet</li>


## Assignment 3: Hello Vectors
In this assignment I explored word vectors. In natural language processing, each word is represented as a vector consisting of numbers. The vector encodes the meaning of the word. These numbers (or weights) for each word are learned using various machine learning models. I used some machine learning models. In the real world, I can always load the trained word vectors, and I will almost never have to train them from scratch. In this assignment, I

<li>Predict analogies between words.</li>
<li>Use PCA to reduce the dimensionality of the word embeddings and plot them in two dimensions.</li>
<li>Compare word embeddings by using a similarity measure (the cosine similarity).</li>
<li>Understand how these vector space models work.</li>


## Assignment 4 - Naive Machine Translation and LSH
I implemented my first machine translation system and then I saw how locality sensitive hashing works.
This assignment covers the folowing topics:
<ol>
<li>The word embeddings data for English and French words</li>
  <ol><li>Generate embedding and transform matrices</li></ol>
<li>Translations</li>
  <ol><li>Translation as linear transformation of embeddings</li>
    <li>Testing the translation</li></ol>
<li>LSH and document search</li>
  <ol><li>Getting the document embeddings</li>
  <li>Looking up the tweets</li>
  <li>Finding the most similar tweets with LSH</li>
  <li>Getting the hash number for a vector</li>
  <li>Creating a hash table</li>
  <li>Creating all hash tables</li></ol>
</ol>




