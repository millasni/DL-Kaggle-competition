# DL-Kaggle-competition
This was an in-class Kaggle competition for Deep Learning, a PhD level course at HEC Montreal.
We had to predict to which class an article belongs (among 5 classes) given its title and reference network. 

In this project, I implemented:

* CNN
* LSTM
* GRU
* BERT
* Text mining (logistic regression, Naive Bayes and multi-layer perceptron based on TF-IDF and bag-of-word matrices)

Some models learnt word embeddings from scratch and some were using pre-trained GloVe and Word2Vec embeddings that were allowed to train further. The latter, however, did not bring a measurable gain in accuracy.

Using atricle titles with reference network allowed getting superior results compared with using only article titles themselves.
