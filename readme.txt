Fake news identifier using LSTM guided Recurrent neural network

Dataset: https://www.kaggle.com/c/fake-news/data?select=train.csv

Tutorial: https://www.youtube.com/watch?v=MXPh_lMRwAI

Code: https://drive.google.com/file/d/1vYOvpyLAZfqb9zSdJk9loWTzXWZM2nK-/view?usp=sharing

Accuracy : 91%


Steps
Preprocessing - all small caps , split,steming word

model:
One hot representation of text data(index number based on vocab) + padding(pre)-  embedding layer(40 vector features)- LSTM



Loss - binary cross entropy
Optimizer: adam


10 epochs
Batch size - 64
Training accuracy: 99
Val accuracy: 91




-	Created an LSTM-guided Recurrent Neural Network for accurately discerning fake news from genuine articles, attaining a robust 91% accuracy
-	Implemented NLTK stemming for preprocessing, combined with one-hot encoding, embedding layers, and LSTM units, to accurately identify fake news.

