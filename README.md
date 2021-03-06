# mxnet-the-straight-dope
Much easy, so MXNet. Wow.

## Abstract
MXNet is widely used in production environments owing to its strong reputation for speed. Now with ``gluon``, MXNet's new imperative interface (alpha), doing research in MXNet is easy. 

This repo contains an incremental sequence of tutorials to make learning ``gluon`` easy (meta-easy?). These tutorials are designed with public presentations in mind and are composed as Jupyter notebooks where each notebook corresponds to roughly 20 minutes of rambling and each codeblock could correspond to roughly one slide.

## Inspiration 

In creating these tutorials, I've borrowed heavily from some of the resources that were most useful when I learned how to program with Theano and PyTorch, specifically:

* [Soumith Chintala's helladope "Deep Learning with PyTorch: A 60 Minute Blitz"](http://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)
* [Alec Radford's bare-bones intro to Theano](https://github.com/Newmu/Theano-Tutorials) 
* [Video of Alec's awesome intro to deep learning with Theano](https://www.youtube.com/watch?v=S75EdAcXHKk)

## Dependencies

To run these notebooks, you'll want to build MXNet from source. Fortunately, this is easy (especially on Linux) if you follow [these instructions](http://mxnet.io/get_started/install.html). You'll also want to [install Jupyter](http://jupyter.readthedocs.io/en/latest/install.html) and use Python 3 (because it's 2017). 

## Table of contents 

### Part 1: Crashcourse 
* [Introduction](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/S01-C01-introduction.md)
* ***Roadmap*** [Linear Algebra](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P01-C02-linear-algebra.ipynb)
* ***Roadmap*** [Probability and Statistics](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P01-C03-probability-statistics.ipynb)

### Part 2: Introduction to Supervised Learning
* [1 - Manipulating data with NDArray](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P02-C01-ndarray.ipynb) 
* [2 - Automatic differentiation via ``autograd``](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P02-C02-autograd.ipynb)
* [3 - Linear Regression *(from scratch!)*](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P02-C03-linear-regression-scratch.ipynb)
* [4 - Linear Regression *(with ``gluon``!)*](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P02-C04-linear-regression-gluon.ipynb)
* [5 - Multiclass Logistic Regression *(from scratch!)*](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P02-C05-softmax-regression-scratch.ipynb)
* [6 - Multiclass Logistic Regression *(with ``gluon``!)*](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P02-C06-softmax-regression-gluon.ipynb)

### Part 3: Deep neural networks (DNNs)
* [1 - Multilayer Perceptrons *(from scratch!)*](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P03-C01-mlp-scratch.ipynb)
* [2 - Multilayer Perceptrons *(with ``gluon``!)*](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P03-C02-mlp-gluon.ipynb)
* ***Roadmap*** Weight Decay and Dropout Regularization (from scratch)
* ***Roadmap*** Weight Decay and Dropout Regularization (from with ``gluon``)

### Part 4: Convolutional neural networks (CNNs)
* [1 - Convolutional Neural Network *(from scratch!)*](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P04-C01-cnn-scratch.ipynb)
* [2 - Convolutional Neural Network *(with ``gluon``!)*](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P04-C02-cnn-gluon.ipynb)
* ***Roadmap*** Batch Normalization (from scratch)
* ***Roadmap*** Batch Normalization (from with ``gluon``)

### Part 5: Recurrent neural networks (RNNs)
* [1 - Simple RNNs and their application to language modeling](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/P05-C01-simple-rnn.ipynb)
* ***Roadmap*** Simple RNNs (with ``gluon``)
* ***Roadmap*** LSTMS (from scratch)
* ***Roadmap*** LSTMS (with ``gluon``)
* ***Roadmap*** GRUs (from scratch) 
* ***Roadmap*** GRUs (with ``gluon``) 
* ***Roadmap*** Dropout for recurrent nets
* ***Roadmap*** Zoneout regularization

### Part 6: Computer vision (CV)
* ***Roadmap*** Network of networks (inception & co)
* ***Roadmap*** Residual networks
* ***Roadmap*** Object detection (SSD & Yolo)
* ***Roadmap*** Fully-convolutional networks
* ***Roadmap*** Siamese (conjoined?) networks
* ***Roadmap*** Embeddings (pairwise and triplet losses)
* ***Roadmap*** Inceptionism / visualizing feature detectors
* ***Roadmap*** Style transfer

### Part 7: Natural language processing (NLP)
* ***Roadmap*** Word embeddings (Word2Vec)
* ***Roadmap*** Sentence embeddings (SkipThought)
* ***Roadmap*** Sentiment analysis
* ***Roadmap*** Sequence-to-sequence learning (machine translation)
* ***Roadmap*** Sequence transduction with attention (machine translation)
* ***Roadmap*** Named entity recognition 
* ***Roadmap*** Image captioning
 
### Part 8: Autoencoders
* ***Roadmap*** Introduction to autoencoders
* ***Roadmap*** Convolutional autoencoders (introduce upconvolution)
* ***Roadmap*** Denoising autoencoders
* ***Roadmap*** Variational autoencoders

### Part 9: Adversarial learning
* ***Roadmap*** Finding adversarial examples
* **Roadmap** Adversarial training

### Part 10: Generative adversarial networks (GANs)
* ***Roadmap*** Introduction to GANs
* ***Roadmap*** DCGAN
* ***Roadmap*** Wasserstein-GANs
* ***Roadmap*** Energy-based GANS
* ***Roadmap*** Conditional GANs
* ***Roadmap*** Image transduction GANs (Pix2Pix)
* ***Roadmap*** Learning from Synthetic and Unsupervised Images 

### Part 11: Deep reinforcement learning (DRL)
* ***Roadmap*** Introduction to reinforcement learning
* ***Roadmap*** Deep contextual bandits
* ***Roadmap*** Deep Q-networks
* ***Roadmap*** Policy gradient
* ***Roadmap*** Actor-critic gradient

### Part 12: Variational methods and uncertainty
* ***Roadmap*** Dropout-based uncertainty estimation (BALD)
* ***Roadmap*** Weight uncertainty (Bayes-by-backprop)
* ***Roadmap*** Variational autoencoders

### Part n: Optimization
* SGD
* Momentum
* AdaGrad
* RMSProp
* Adam 
* AdaDelta
* SGLD / SGHNT

### Part 13: Optimization, Distributed and high-performance learning
* ***Roadmap*** Optimization Algorithms (Adam, AdaGrad, 
* ***Roadmap*** Training with Multiple GPUs 
* ***Roadmap*** Training with Multiple Machines
* ***Roadmap*** Combining imperative deep learning with symbolic graphs

### Part 14: Recommender systems
* ***Roadmap*** Latent factor models
* ***Roadmap*** Deep latent factor models
* ***Roadmap*** Bilinear models
* ***Roadmap*** Learning from implicit feedback

### Part m: Time series
* Forecasting
* Modeling missing data
* Combining static and sequential data

### Appendix 1: Cheatsheets
* ***Roadmap*** ``gluon`` 
* ***Roadmap*** PyTorch to MXNet
* ***Roadmap*** Tensorflow to MXNet
* ***Roadmap*** Math to MXNet


## Choose your own adventure
I've designed these tutorials so that you can traverse the curriculum in one of three ways.
* Anarchist - Choose whatever you want to read, whenever you want to read it.
* Imperialist - Proceed through all tutorials in order. In this fashion you will be exposed to each model first from scratch, writing all the code ourselves but for the basic linear algebra primitives and automatic differentiation.
* Capitalist - If you don't care how things work (or already know) and just want to see working code in ``gluon``, you can skip (*from scratch!*) tutorials and go straight to the production-like code using the high-level ``gluon`` front end.


## Authors
This evolving creature is a collaborative effort. Some amount of credit (and blame) can be shared by:
* Zachary C. Lipton ([@zackchase](https://github.com/zackchase))
* Mu Li ([@mli](https://github.com/mli))
* Alex Smola ([@smolix](https://github.com/smolix))
* Eric Junyuan Xie ([@piiswrong](https://github.com/piiswrong))
