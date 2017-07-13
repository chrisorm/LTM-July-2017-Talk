# LTM July 2017 Talk 

## Overview
This repository has the code that accompanies the LTM talk on text classification with RNNs.

This is intended to demonstrate how to go about implementing many of the recently developed architectures in Deep NLP. There are many more complex combinations of these tools you could use - mix and match should be quite straight forward.

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
