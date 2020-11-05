## Sentiment analysis on IMDB dataset using RNN

# Create a recurrent neural network that is able to classify a movie review as either positive or negative.

# RNN
A recurrent neural network (RNN) is a class of artificial neural networks where connections between nodes form a directed graph along a temporal sequence. Derived from feedforward neural networks, RNNs can use their internal state (memory) to process variable length sequences of inputs.

# Sentiment Analysis

Sentiment analysis aims to determine the attitude, or sentiment. For example, a speaker or writer with respect to a document, interaction, or event. It is a natural language processing problem in which text needs to be understood to predict the underlying intent.

The dataset contains a collection of 50,000 reviews from IMDB and contains an even number of positive and negative reviews. A negative review has a score of ≤ 4 out of 10 and a positive review has a score of ≥ 7 out of 10. Neutral reviews are not included in the dataset.
The dataset is divided into training and test sets. The training set is the same 25,000 labelled reviews.

1. Preprocessing.
2. Build a RNN Model for Sentiment Analysis.
3. Train the model. 
4. Test the model - evaluate the model on test data.
5. Make predictions.
6. Classify an unseen movie review, via an input string, as positive or negative.
