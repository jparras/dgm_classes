# DGM codes
Codes used for teaching about Deep Generative Models (DGM). All algorithms are coded using Torch. Note that these algorithms are for pedagogical purposes, so they might not be the best in terms of performance and/or efficiency.

## Simple models
These codes are intended to understand some of the basic principles underlying a Generative Model and classical methods used to sample from distributions. 
* [Gaussian mixture](/simple_models/gaussian_mixture.ipynb) presents the simple case of having a Gaussian Mixture Model.
* [Gibbs sampling of a bivariate Gaussian](/simple_models/gibbs_gaussian.ipynb) shows an step-by-step implementation of a Gibbs sampler on a bivariate Gaussian distribution.
* [Gibbs sampling of a hierarchical Gaussian](/simple_models/gibbs_hierarchical_gaussian.ipynb) shows another step-by-step implementation of a Gibbs sampler, in this case applied to inferring the parameters of a hierarchical Gaussian distribution. This exercise highlights that Gibbs can be used to sample from an unknwown posterior, provided that we can sample from the conditional distributions.
* [E-M example on a Gaussian mixture](/simple_models/gaussian_mixture_em.ipynb) particularizes the E-M algorithm to a Gaussian Mixture model and implements the method step-by-step.
* [E-M example on a Gaussian mixture](/simple_models/gaussian_mixture_em.ipynb) particularizes the E-M algorithm to a Gaussian Mixture model and implements the method step-by-step.
* [Estimation of a noisy vector](/simple_models/unknown_vector_inference.ipynb) shows an inference example of an unknown vector from noisy measurements.
* [VI with MF on a hierarchical Gaussian](/simple_models/vi_mean_field.ipynb) shows an example of Variational Inference using a Mean-Field approximation on a hierarchical Gaussian distribution.

## DGM models
These coes are intended to understand and exemplify some of the key ideas used in Deep Generative models. Hence, the methods used are simplified so as to maximize the understanding of the principles underlying these methods, and their performance is clearly limited against state-of-the-art implementations. 
* [Linear flow with Gaussian data](/dgm/linear_flow_gaussian.ipynb) shows how to implement a simple linear flow to transform a Gaussian distribution into another one, making special emphasis on the random variable transformation involved.
* [Linear Autoencoder with MNIST](/dgm/linear_ae_mnist.ipynb) implements a Linear Autoencoder and trains it on the MNIST data. It also explores how the latent representation affects the quality of the reconstruction.

## PASD students guide

| Example      | Link |
| ----------- | ----------- |
| 1.5      | [Gaussian mixture](/simple_models/gaussian_mixture.ipynb)       |
| 1.6   | [Gibbs sampling of a bivariate Gaussian](/simple_models/gibbs_gaussian.ipynb)        |
| 1.7   | [Gibbs sampling of a hierarchical Gaussian](/simple_models/gibbs_hierarchical_gaussian.ipynb)       |
| 2.4   | [E-M example on a Gaussian mixture](/simple_models/gaussian_mixture_em.ipynb)       |
| 2.9   | [Estimation of a noisy vector](/simple_models/unknown_vector_inference.ipynb)       |
| 2.13  | [VI with MF on a hierarchical Gaussian](/simple_models/vi_mean_field.ipynb)       |
| 3.4   | [Linear flow with Gaussian data](/dgm/linear_flow_gaussian.ipynb)       |
| 3.5   | [Linear Autoencoder with MNIST](/dgm/linear_ae_mnist.ipynb)       |


# Execution in Google Colab

The recommended way of executing these codes is to use Google Colab. The simplest way of doing that is to navigate to the code you want to execute, and then replace `github.com` in the URL by `githubtocolab.com`.

A second option is to go to Colab, and in the Open options, select Github and add this repository.

And finally, you can also download the code and execute it in your own machine, by installing all required dependencies.
