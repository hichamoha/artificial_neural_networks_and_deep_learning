# Artificial Neural Networks and Deep Learning

This repository provides an introduction to the field of Artificial Neural Networks and Deep Learning. It covers the most common models in artificial neural networks with a focus on the multi-layer perceptron. The repo also provides an introduction to deep learning: An overview of convolutional neural networks (CNN) for classification of images, different techniques to avoid overtraining in deep networks, techniques to pre-train deep networks

The material are based on the text book *Deep Learning* by Goodfellow et al., as well as on the lecture notes from the department of *Astronomy and Theoretical Physics at LTH, Lund University*. An HTLM version of the book (Ian Goodfellow, Yoshua Bengio, Aaron Courville: Deep Learning) is available at https://www.deeplearningbook.org/ 

The main topics of the content included in this material can be summarized by the following:

## Feed-forward Neural Networks
We will start with the simple perceptron and then move onto the multi-layer perceptron. Will will look at the choice of suitable error functions and techniques to minimize them, how to detect and avoid overtraining, ensembles of neural networks and techniques to create them, Bayesian training of multi-layer perceptrons. 

##  CNN, Autoencoder and GAN
Convolutional Neural Networks (CNN) are mostly used for image analysis. There is a special MLP, called an autoencoder, that has the same number of output nodes as the inputs. The hidden layer, called bottleneck, always have a smaller size compared to the input size. The main usage of the GAN is to
be able to generate samples. The Generative Adversarial Networks (GAN) actually consists of two networks, called the generator network and the discriminator network.

## Recurrent Neural Networks
We will now study networks with **feedback connections**. Recurrent networks are typically used when we are dealing with **sequence data**. It can be text data, speech data or numerical times series data coming from eg. sensors or stock markets. The feedback connections are used to capture the short and long term temporal dependencies in the data. We will look at simple recurrent networks and their use in time series analysis, fully recurrent for both time series analysis and associative memories (Hopfield model), the simulated annealing optimization technique. 

## Self-Organizing Neural Networks
In unsupervised learning there is no teacher! “The purpose of an algorithm for self-organized (or unsupervised) learning is to discover significant features or patterns in the input data and todo the discovery without a teacher”. We will look at networks that can extract principal components, networks for data clustering, learning vector quantization (LVQ), self-organizing feature maps (SOFM). 
