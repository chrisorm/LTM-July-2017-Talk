# LTM July 2017 Talk 
## Specs

* Python 3.5
* Tensorflow 1.2

## Overview
This repository has the code that accompanies the LTM talk on text classification with RNNs.

This is intended to demonstrate how to go about implementing many of the recently developed architectures in Deep NLP. There are many more complex combinations of these tools you could use - mix and match should be quite straight forward.

This is not intended to be a best practice guide, exceptionally cutting edge or most efficient. Its meant to be easy to follow and to encourage people to get stuck in!

### Basic RNN cell
* **BasicRNN** - A simple RNN classifier using BasicRNNCell
* **BasicBidirectionalRNN** - A Bidirectional RNN classifier using BasicRNNCell
* **BasicBidirectionalRNN-MeanPooling** - A Bidirectional RNN with Mean pooling to aggregate hidden states
* **BasicBidirectionalRNN-MaxPooling** - A Bidirectional RNN with Max pooling to aggregate hidden states
* **BasicRNNAttention** - A unidirectional RNN with attention mechanism

### GRU cell

* **GRURNN** - A GRU RNN classifier using GRUCell
* **GRUBidirectionalRNN-MeanPooling** - A Bidirectional GRU RNN with Mean pooling to aggregate hidden states
* **GRUBidirectionalRNN-MaxPooling** - A Bidirectional GRU RNN with Max pooling to aggregate hidden states

### LSTM cell
* **LSTMRNN** - An RNN classifier using LSTMCell


## Suggested Syllabus

### Lesson 1 
* Lecture 8 of CS224n [Slides](http://web.stanford.edu/class/cs224n/lectures/cs224n-2017-lecture8.pdf)
* WildML blog of RNNs in Tensorflow. [Blog](http://www.wildml.com/2016/08/rnns-in-tensorflow-a-practical-guide-and-undocumented-features/) - Some features/locations may have changed between tensorflow versions.
* Read the documentation about dynamic_rnn, and cell types, on tensorflow website. [dynamic_rnn](https://www.tensorflow.org/api_docs/python/tf/nn/dynamic_rnn) [BasicRNNCell](http://web.stanford.edu/class/cs224n/lectures/cs224n-2017-lecture9.pdf)

#### Exercises
* **BasicRNN**


### Lesson 2
* Lecture 9 CS224n [Slides](http://web.stanford.edu/class/cs224n/lectures/cs224n-2017-lecture9.pdf)
* Colah's Blog on LSTMs [Blog](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* Read the documentation about GRUs and LSTMs, on tensorflow website. [LSTM](https://www.tensorflow.org/api_docs/python/tf/contrib/rnn/LSTMCell) [GRU](https://www.tensorflow.org/api_docs/python/tf/contrib/rnn/GRUCell)

#### Exercises
* **GRURNN**
* **LSTMRNN**

### Lesson 3

#### Exercises
* **BasicBidirectionalRNN** 
* Modify this code to run bidirectional LSTM and GRU networks.

### Lesson 4

#### Exercises
* **BasicBidirectionalRNN-MeanPooling**
* **BasicBidirectionalRNN-MaxPooling** 
* **GRUBidirectionalRNN-MeanPooling**
* **GRUBidirectionalRNN-MaxPooling**

### Lesson 5

#### Exercises
* **BasicRNNAttention**
* Modify this code to run attention over an LSTM network.

### Lesson 6+
Apply these techniques to other datasets, some examples:
#### Exercises

* Yelp dataset [Site](https://www.yelp.co.uk/dataset_challenge)
* Hierichal text classification [Kaggle](https://www.kaggle.com/c/lshtc)
* Reuters Dataset [Site](http://www.daviddlewis.com/resources/testcollections/reuters21578/)

### This is a work in progress - please raise an issue for any errors.
