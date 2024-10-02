# Word generative models


The initial implementation was a bigram model that computes the next character when given a single character as a one hot endcoded vector input. This was further extended by building a multi layer perceptron which takes in three charcters and predicts the fourth character.

YaGPT contains code for a character-level language model designed to predict the next character in a sequence, based on the input provided. It employs a Multi-layer Perceptron (MLP), to model sequential data at the character level. The model takes a sequence of characters as input, processes the sequence through multiple fully connected layers, and generates a probability distribution over the possible next characters. In addition to the core MLP architecture, Wordgen also integrates an attention mechanism coded from scratch. This attention layer allows the model to focus on different parts of the input sequence when making predictions.

This implementation is based on Andrej Karpathy's nanoGPT tutorial. (https://www.youtube.com/watch?v=kCc8FmEb1nY&t=3994s)
