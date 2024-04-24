# Introduction
This repository represents my work done while completing the Natural Language Processing with Deep Learning course.
I follow the 2021 versions for Assignment 1 and 2, the Winter 2024 version for assignment 3, and Spring 2024 version for Assignment 4. All the material is available here [https://web.stanford.edu/class/cs224n/](https://web.stanford.edu/class/cs224n/)

Enjoy the code and the math :wink:

# Links
## Assignment 1
[Problem statement and my solution](a1/exploring_word_vectors.ipynb) :scroll:

This assignment is about exploring the idea of representing words as vectors. Several methods of embedding a word into a vector are put to the test and are visualized using dimenionality reduction. Examined word embedding methodologies are:
1. co-occurence word embeddings
2. prediction based word embeddings (word2vec, GloVe)

## Assignment 2
This assignment studies two loss functions for calculating the accuracy of two prediction-based word embedding techniques: 1) naive-softmax and 2) negative-sampling. The derivatives of the loss functions with respect to all the parameters are then computed to allow the implementation of stochastic gradient descent and to create a word embedding model from scratch.

[Problem statement](a2/a2.pdf) :closed_book:

### My work

[Latex type-set pdf answering the written portion of the assignment](a2/a2_solution.pdf) :scroll:

[Implementation of word2vec](a2/word2vec.py) :arrow_upper_right:

[Implementation of stochastic gradient descent](a2/sgd.py) :mountain:


## Assignment 3
This assignment contains a theoretical and practical part. 

- Theoretical: we explore how learning can be improved using Adam Optimizer and Dropout. 
- Practical: we create a Neural Network model that predicts the dependencies of words in sentences. The dependency parsing model finds the dependencies by using a transition mechanism. More precisely, the model predicts the next transition from the current state of the parsing.

### My work

[Write-up of the assignment containing my answers](a3/solution_cs224n_a3_student_latex.pdf) :scroll:

[Transition mechanism between the parser states](a3/a3_student_code/parser_transitions.py)  :arrow_heading_down:

[Neural network predicting which transition to apply](a3/a3_student_code/parser_model.py) :brain:

[Model training code using Adam optimizer](a3/a3_student_code/run.py) :weight_lifting:
