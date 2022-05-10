# Deep Learning Notebooks

## Description

The basic rationale behind these notebooks is to demonstrate how deep learning concepts might be implemented in a library.

The only libraries used for calculations are `numpy` and `cupy`.

## Outline

* `neural-networks.ipynb`: Contains pure *numpy* implementations of basic neural network concepts such as:
  * Activation functions
  * Loss functions
  * Fully-connected layers (forward and backward passes)
  * Convolution/Pooling layers (forward and backward passes)

***Note:** Some notebooks have been GPU-accelerated with the use of [CuPy](https://github.com/cupy/cupy) in order to perform model training faster.*


## Future

### Part 1

***Due:** 18th May 2022*

1. Move concepts and experiments code into separate notebooks.
2. Simplify functions and reduce OOP language.
3. Upload code for experiments 1, 2, and 3.
4. Implement code for:
   1. Regularization
   2. Batch normalization
   3. Drop-out
5. Refactor code for convolution.

### Part 2

***Due:** 25th May 2022*

1. Implement code for:
   1. Class activation map
   2. Word embeddings
      1. Bag of Words
      2. Neural Probabilistic Model
      3. Word2vec
      4. Continuous Skip-Gram
   3. Language models
   4. Recurrent Neural Networks
      1. Long Short-Term Memory
      2. Gated Recurrent Unit
   5. Self-attention
   6. Transformer

### Part 3

***Due:** 1st June 2022*

1. Implement code for:
   1. Graph embeddings
      1. Node2vec
      2. [...]
   2. Graph convolution networks
      1. Graph filters
      2. Graph pooling
   3. Graph models
