# DeepLearning_TV_ScriptGeneration

## Overview
Created original Seinfeld TV scripts using RNNs. 
The dataset used part of the Seinfeld dataset of scripts from 9 seasons. 
The Neural Network generates a new ,"fake" TV script, based on patterns it recognizes in this training data.

## Architecture details
The architecture chosed is an RNN that uses LSTM 
### Training parameters
* num_epochs = 15
* learning_rate = 0.001 

### Model parameters
* vocab_size = len(vocab_to_int)
* output_size = vocab_size
* embedding_dim = 300 
* hidden_dim = 300 
* n_layers = 2

### Results
The generated scripts are far from ideal, but they are pretty convincing.
