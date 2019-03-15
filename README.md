This repository contains my own implementation of machine learning algorithms that stimulate my interest.
At the beginning of each notebook you will find a reference to the paper that describes the algorithm.
My goal is not to reproduce every singe table and figure in the paper, I am satisfied when I have enough evidence that my implementation is correct.
Sometimes the notebooks are not very refined because I try to limit the amount of time I work on a paper, because I lose interest, because I find something else that diverts my attention, etc.
The current implementations are:
 - `bayes_by_backprop.ipynb`: Charles Blundell et al., _Weight Uncertainty in Neural Networks_, May 2015. Pure numpy implementation for linear regression, tensorflow and pymc3 on MNIST.
 - `coteaching.ipynb`: Bo Han et al., _Co-teaching: Robust Training of Deep Neural Networks with Extremely Noisy Labels_, 2018. Implemented in keras.
 - `deep_gaussian_processes.ipynb`: Jaehoon Lee, Yasaman Bahri, Roman Novak, Samuel S. Schoenholz, Jeffrey Pennington, Jascha Sohl-Dickstei, _Deep Neural Networks as Gaussian Processes_, International Conference of Learning Representation, 2018. Implemented in numpy and tested on subsamples of MNIST, also includes hyper-parameter optimization using gpyopt.
 - `relevance_vector_machine.ipynb`: Tipping, Michael E. (2001). _Sparse Bayesian Learning and the Relevance Vector Machine_. Journal of Machine Learning Research. 1: 211–244. Implementation in numpy, both for classification and regression.
 - `sparse_gaussian_processes.ipynb`: M. K. Titsias. _Variational learning of inducing variables in sparse Gaussian processes_, Proceedings of the Twelfth International Conference on Artificial Intelligence and Statistics. 2009. Implemented in numpy and tensorflow.