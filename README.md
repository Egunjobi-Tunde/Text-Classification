# Text-Classification

### Dataset: 
https://www.kaggle.com/datasets/thedevastator/yelp-reviews-sentiment-dataset?rvi=1 

A random sample of 4000 Yelp-reviews-sentiment datasets was used to reduce the cost of computation.  

### Preprocessing
SpaCy, a popular NLP library, was used to clean and preprocess the data. This includes removing special characters, figures, stopwords, and punctuation. 

### Vectorization
TF-iDF was used to vectorize the data: conversion of Text to Vectors of figures

### Dataset and DataLoader
The Pytorch dataset and Dataloader were used to load the vectors and the label into batch sizes in the train and test datasets.
### Model
A Multi-Layer Perceptron was designed and trained to classify the reviews into positive and negative reviews.
