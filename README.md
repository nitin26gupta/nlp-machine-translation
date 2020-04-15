# Introduction
Deep neural network that functions as part of an end-to-end machine translation pipeline. Completed pipeline accepts English text as input and return the French translation.

# Setup

This project requires GPU acceleration to run efficiently. 

## Install
- Python 3
- NumPy
- TensorFlow 2.x
- Keras 2.x

## Preprocess
Text is converted to Integers integers.Tokenize the words into idsAdd padding to make all the sequences the same length.

## Padding
The English sequences should have the same length and all the French sequences should have the same length, this is achieved using pad_sequences function.

# Models 
Multiple different models are created which accepts a sequence of integers as input and returns a probability distribution over possible translations.

Model 1 is a simple RNN
Model 2 is a RNN with Embedding
Model 3 is a Bidirectional RNN
Model 4 is an Encoder-Decoder RNN
Model 5 incorporates embedding and a bidirectional rnn

## Prediction 
Run the model on English text.
