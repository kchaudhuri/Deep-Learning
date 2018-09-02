
In this project of Sentiment Analysis we go through the following stages:


Stage 1 - Data Processing

1) Reading the Data.

2) Building a Dictionary - Word : Number of appearances.

3) Building a List of all possible words.

4) Giving all the words its corresponding index by building a Dictionary - Word : Index.

5) Converting the sentence from its text to vector form.

6) Converting the whole dataset from text to vector.

7) Splitting the data to training and test set.


Stage 2 - Building and training model

8) Building a DNN model layer by layer.

9) Training the model.


Stage 3 - Inference

10) Tested the model on the testing dataset with an accuracy of 77.52 %.


Areas of improvements:

1) This model is not an entirely accurate model since it does not regard the data as a sequence of text, thus the the context is lost and the sentiment analysis is conducted with a naive approach. Therefore an RNN with LSTMs will be a better model for this project.
