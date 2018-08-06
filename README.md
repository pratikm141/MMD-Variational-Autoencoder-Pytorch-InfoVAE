# Pytorch Implementation of MMD Variational Autoencoder

The Code has been converted from the TensorFlow [implementation](https://github.com/ShengjiaZhao/MMD-Variational-Autoencoder) by [Shengjia Zhao](https://github.com/ShengjiaZhao)

-----------------------------------------------------------------------------------------------------------------------------
Details and motivation are described in this [paper](https://arxiv.org/abs/1706.02262) or [tutorial](http://szhao.me/2017/06/10/a-tutorial-on-mmd-variational-autoencoders.html). For your convenience the same code is provided in both python and ipython.
----------------------------------------------------------------------------------------------------------------------------
This implementation trains on MNIST, generating reasonable quality samples after 27 epochs of training
![mnist](plots/generation.png)

When latent dimensionality is 2, we can also visualize the distribution of labels in the feature space. 

## Before Training
![mnist](plots/scatter-before-training_classic.png)

## After Training
![mnist](plots/scatter-after-training_classic.png)

