# VAE_DogImages
Variational Autoencoder for Generating Dog Images: This repository contains the implementation of a VAE model to generate images of dogs


### Variational Autoencoder for Generating Dog Images

This repository contains the implementation of a Variational Autoencoder (VAE) model to generate images of dogs. The model uses TensorFlow and Keras for training and image generation, with custom loss functions and visualization.

## Introduction

DogVAE-Generator is a project that leverages a Variational Autoencoder (VAE) to generate realistic images of dogs. The VAE is trained on a dataset of dog images and can generate new dog images by sampling from the learned latent space.

## Model Architecture

The VAE model comprises:
- **Encoder**: Maps input images to a latent space.
- **Decoder**: Maps points in the latent space back to the image space.
- **Loss Function**: Combines reconstruction loss (binary cross-entropy) and KL divergence.



