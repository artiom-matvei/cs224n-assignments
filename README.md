# Introduction
This repository represents my work done in order to follow the course Natural Language Processing with Deep Learning.
The 2021 version of the course was followed as it had all the material available online: https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1214/

Enjoy the code and the math ;)

# Links
## Assignment 1
[Problem statement and my solution](a1/exploring_word_vectors.ipynb)

This assignment is about exploring the idea of representing words as vectors. Several methods of embedding a word into a vector are put to the test and are visualized using dimenionality reduction. Examined word embedding methodologies are:
1. co-occurence word embeddings
2. prediction based word embeddings (word2vec, GloVe)

## Assignment 2
This assignment studies two loss functions for calculating the accuracy of two prediction-based word embedding techniques: 1) naive-softmax and 2) negative-sampling. The derivatives of the loss functions with respect to all the parameters are then computed to allow the implementation of stochastic gradient descent and to create a word embedding model from scratch.

[Problem statement](a2/a2.pdf)

### My work

[Latex type-set pdf answering the written portion of the assignment](a2/a2_solution.pdf)

[Implementation of word2vec](a2/word2vec.py)

[Implementation of sgd](a2/sgd.py)
