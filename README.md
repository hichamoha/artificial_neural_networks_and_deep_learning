# Artificial Neural Networks and Deep Learning

This repository provides an introduction to the field of Artificial Neural Networks and Deep Learning. It covers the most common models in artificial neural networks with a focus on the multi-layer perceptron. The material also provides an introduction to deep learning: An overview of convolutional neural networks (CNN) for classification of images, different techniques to avoid overtraining in deep networks, techniques to pre-train deep networks

The material are based on the text book *Deep Learning* by Goodfellow et al., and the course Convolutional Neural Networks for Visual Recognition (CS231N) at Stanford https://cs231n.github.io/neural-networks-1/, as well as on the lecture notes from Computational Biology & Biological Physics (CBBP) in the department of *Astronomy and Theoretical Physics at Lund University*. An HTLM version of the book (Ian Goodfellow, Yoshua Bengio, Aaron Courville: Deep Learning) is available at https://www.deeplearningbook.org/ 

The main topics of the content included in this material can be summarized by the following subparagraphs. In addition, there are two assignments. The first deals with Feed forward networks, classification and regression problems, overtraining, modelselection, etc. The second assignment includes Convolutional neural networks, recurrent networks, images classification, times series analysis, etc. The programs will be run in an environment called *Jupyter notebook*, which it is an interactive computing environment. In order to get the Jupyter notebook we need to install ”Anaconda”, which is a ”Python Data Science Platform”. After installing Anaconda on our computer, we need also to install the Tensorflow and Keras libraries. Tensorflow is a "low-level" library for machine Learning, whereas Keras is a "high-level" library for Deep Learning (i.e. Neural Networks).

## Feed-forward Neural Networks
We will start with the simple perceptron and then move onto the multi-layer perceptron. Will will look at the choice of suitable error functions and techniques to minimize them, how to detect and avoid overtraining, ensembles of neural networks and techniques to create them, Bayesian training of multi-layer perceptrons. 

##  CNN, Autoencoder and GAN
Convolutional Neural Networks (CNN) are mostly used for image analysis. Then, we look at a special MLP, called an autoencoder, that has the same number of output nodes as the inputs. The hidden layer, called bottleneck, always have a smaller size compared to the input size. The main usage of the Generative Adversarial Networks (GAN) is to be able to generate samples. The GAN actually consists of two networks, called the generator network and the discriminator network.

## Recurrent Neural Networks
Here, we will now study networks with **feedback connections**. Recurrent networks are typically used when we are dealing with **sequence data**. It can be text data, speech data or numerical times series data coming from eg. sensors or stock markets. The feedback connections are used to capture the short and long term temporal dependencies in the data. We will look at simple recurrent networks and their use in time series analysis, fully recurrent for both time series analysis and associative memories (Hopfield model), the simulated annealing optimization technique. 

## Self-Organizing Neural Networks
In unsupervised learning there is no teacher! “The purpose of an algorithm for self-organized (or unsupervised) learning is to discover significant features or patterns in the input data and to do the discovery without a teacher”. We will look at networks that can extract principal components, networks for data clustering, learning vector quantization (LVQ), self-organizing feature maps (SOFM). 
