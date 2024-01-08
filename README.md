# DGM codes
Codes used for teaching about Deep Generative Models (DGM). All algorithms are coded using Torch. Note that these algorithms are for pedagogical purposes, so they might not be the best in terms of performance and/or efficiency.

## Simple models
These codes are intended to understand some basic principles underlying a Generative Model and classical methods used to sample from distributions. 
* [Unidimensional Gaussian](/simple_models/gaussian_unidimensional.ipynb) presents a simple case using a unidimensional Gaussian distribution.
* [Gaussian mixture](/simple_models/gaussian_mixture.ipynb) presents the simple case of having a Gaussian Mixture Model.
* [Gibbs sampling of a bivariate Gaussian](/simple_models/gibbs_gaussian.ipynb) shows a step-by-step implementation of a Gibbs sampler on a bivariate Gaussian distribution.
* [Gibbs sampling of a hierarchical Gaussian](/simple_models/gibbs_hierarchical_gaussian.ipynb) shows another step-by-step implementation of a Gibbs sampler, in this case applied to inferring the parameters of a hierarchical Gaussian distribution. This exercise highlights that Gibbs can be used to sample from an unknwown posterior, provided that we can sample from the conditional distributions.
* [E-M example on a Gaussian mixture](/simple_models/gaussian_mixture_em.ipynb) particularizes the E-M algorithm to a Gaussian Mixture model and implements the method step-by-step.
* [Estimation of a noisy vector](/simple_models/unknown_vector_inference.ipynb) shows an inference example of an unknown vector from noisy measurements.
* [VI with MF on a hierarchical Gaussian](/simple_models/vi_mean_field.ipynb) shows an example of Variational Inference using a Mean-Field approximation on a hierarchical Gaussian distribution.

## DGM models
These codes are intended to understand and exemplify some key ideas used in Deep Generative models. Hence, the methods used are simplified so as to maximize the understanding of the principles underlying these methods, and their performance is clearly limited against state-of-the-art implementations. 
* [Linear flow with Gaussian data](/dgm/linear_flow_gaussian.ipynb) shows how to implement a simple linear flow to transform a Gaussian distribution into another one, making special emphasis on the random variable transformation involved.
* [Linear Autoencoder with MNIST](/dgm/linear_ae_mnist.ipynb) implements a Linear Autoencoder and trains it on the MNIST data. It also explores how the latent representation affects the quality of the reconstruction.
* [Variational Autoencoder with MNIST](/dgm/vae_mnist.ipynb) implements a Variational Autoencoder and trains it on the MNIST data. This example explores the latent space of the VAE, showing some of the insights that it provides.
* [Generative Adversarial Network with MNIST](/dgm/gan_mnist.ipynb) implements a Generative Adversarial Network and trains it on the MNIST data.

## PASD students guide

| Name | Link | Observations            |
| ----------- | ----------- |-------------------------|
| Example 1.3  | [Gaussian mixture](/simple_models/gaussian_mixture.ipynb)       | Example of Chapter 1    |
| Example 1.6  | [Gibbs sampling of a bivariate Gaussian](/simple_models/gibbs_gaussian.ipynb)       | Example of Chapter 1    |
| Case Study 1 | [Unidimensional Gaussian](/simple_models/gaussian_unidimensional.ipynb)       | Case Study of Chapter 2 |
| Case Study 2 | [E-M example on a Gaussian mixture](/simple_models/gaussian_mixture_em.ipynb)       | Case Study of Chapter 2 |
| Case Study 3 | [Gibbs sampling of a hierarchical Gaussian](/simple_models/gibbs_hierarchical_gaussian.ipynb)       | Case Study of Chapter 2 |
| Case Study 4 | [VI with MF on a hierarchical Gaussian](/simple_models/vi_mean_field.ipynb)       | Case Study of Chapter 2 |
| Case Study 5 | [Linear flow with Gaussian data](/dgm/linear_flow_gaussian.ipynb)       | Case Study of Chapter 3 |
| Case Study 6 | [Linear Autoencoder with MNIST](/dgm/linear_ae_mnist.ipynb)       | Case Study of Chapter 3 |
| Case Study 7 | [Variational Autoencoder with MNIST](/dgm/vae_mnist.ipynb)       | Case Study of Chapter 3 |
| Case Study 8 | [Generative Adversarial Network with MNIST](/dgm/gan_mnist.ipynb)       | Case Study of Chapter 3 |


# Execution in Google Colab

The recommended way of executing these codes is to use Google Colab. The simplest way of doing that is to navigate to the code you want to execute, and then replace `github.com` in the URL by `githubtocolab.com`.

A second option is to go to Colab, and in the Open options, select GitHub and add this repository.

And finally, you can also download the code and execute it in your own machine, by installing all required dependencies.
