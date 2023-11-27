# DGM codes
Codes used for teaching about Deep Generative Models (DGM). All algorithms are coded using Torch. Note that these algorithms are for pedagogical purposes, so they might not be the best in terms of performance and/or efficiency.

## Simple models
These codes are intended to understand some of the basic principles underlying a Generative Model and classical methods used to sample from distributions. 
* [Gaussian mixture](/simple_models/gaussian_mixture.ipynb) (PASD: Example 1.5) presents the simple case of having a Gaussian Mixture Model.
* [Gibbs sampling of a bivariate Gaussian](/simple_models/gibbs_gaussian.ipynb) (PASD: Example 1.6) shows an step-by-step implementation of a Gibbs sampler on a bivariate Gaussian distribution.
* [Gibbs sampling of a bivariate Gaussian](/simple_models/gibbs_hierarchical_gaussian.ipynb) (PASD: Example 1.7) shows another step-by-step implementation of a Gibbs sampler, in this case applied to inferring the parameters of a hierarchical Gaussian distribution. This exercise highlights that Gibbs can be used to sample from an unknwown posterior, provided that we can sample from the conditional distributions. 


# Execution in Google Colab

The recommended way of executing these codes is to use Google Colab. The simplest way of doing that is to navigate to the code you want to execute, and then replace `github.com` in the URL by `githubtocolab.com`.

A second option is to go to Colab, and in the Open options, select Github and add this repository.

And finally, you can also download the code and execute it in your own machine, by installing all required dependencies.
