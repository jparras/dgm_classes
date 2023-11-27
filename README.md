# DGM codes
Codes used for teaching about Deep Generative Models (DGM). All algorithms are coded using Torch. Note that these algorithms are for pedagogical purposes, so they might not be the best in terms of performance and/or efficiency.

## Simple models
The algorithms implemented for model-free DRL are the following (all tested on the Cartpole problem):
* [DDQN](/model_free/DDQN_cartpole.ipynb) (Double Deep Q-Networks)
* [VPG](/model_free/VPG_cartpole.ipynb) (Vanilla Policy Gradient)
* [A2C](/model_free/A2C_cartpole.ipynb) (Advantage Actor Critic)
* [TRPO](/model_free/TRPO_cartpole.ipynb) (Trust Region Policy Optimization, note that in this case, we use the implementation of Stable Baselines 3 instead of providing an implementation to show a state-of-the-art library)
* [DDPG](/model_free/DDPG_cartpole.ipynb) (Deep Deterministic Policy Gradient)

# Execution in Google Colab

The recommended way of executing these codes is to use Google Colab. The simplest way of doing that is to navigate to the code you want to execute, and then replace `github.com` in the URL by `githubtocolab.com`.

A second option is to go to Colab, and in the Open options, select Github and add this repository.

And finally, you can also download the code and execute it in your own machine, by installing all required dependencies.
