# DeepCover
Uncover Bugs in Deep Learning

DeepCover is a coverage-based bug finder for deep learning applications.
It is able to provide metrics for evaluating the robustness of a Deep Neural Network (DNN).
The basic idea of DeepCover is easy. For any neuron in the DNN, if its state changes,
there must be a cause for it: DeepCover aims to COVER these changes and causes.
More details can be found in the paper [Testing Deep Neural Networks](https://arxiv.org/abs/1803.04792).

## To run the tool, the following software or Python package is required:
  theano, numpy, matplotlib, IBM CPLEX

Currently, DeepCover is under development to support TensorFlow.
