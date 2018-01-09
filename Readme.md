# Distilling Tree

Implementation of 2017 Paper:
[Distilling a Neural Network Into a soft Decision Tree](https://arxiv.org/pdf/1711.09784.pdf)

Paper was written by Nicholas Frosst, and Geoffry Hinton from the Google Brain Team.


## Goals:

1. Recreate the paper
2. Study different distributions
3. Embed different neural net layer types in different nodes, such as Conv2D, or others

**TLDR: Structuring a tree with different layers per node to understand the decision process of a neural network **


The general structure of a simple tree with 1 depth. 
<img src='https://snag.gy/z2twL8.jpg' />

Below: after training a sample of the weight distributions. After training (based on MNIST hand-written numbers set)
<img src='https://snag.gy/Oq6zNf.jpg' />
