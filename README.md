# Quora-Insincere-Questions-Classification-Kaggle

Kaggle link to the competion : https://www.kaggle.com/c/quora-insincere-questions-classification

First competition on Kaggle. 

Brief about the competition: Quora is trying to find out insincere questions among thousands of questions that are posted on the website daily. It is a binary classification problem. The dataset contains question's title and its associated class(insincere is 1).  Around 1.3M entries in training data and ~50K in the test.

Approach:

I plan to apply multiple approaches and according to the results analyze and ensemble them.

1.  LSTM using google word2vec for word embedding. Fine tune: embeddings to incorporate the semantics of the available data.

2.  2D sentence CNN using the same embeddings approach as above.

3. Meta embedding: Using multiple embedding(google word2vec, glove, paragraph vectors) and train multiple DL model with just different embedding layer.
