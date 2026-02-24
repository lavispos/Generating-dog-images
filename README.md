# Generating Dog Images with Autoencoders

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lavispos/Generating-dog-images/blob/main/Generating_Dog_Images_with_Autoencoders.ipynb)  
[View on NBViewer](https://nbviewer.org/github/lavispos/Generating-dog-images/blob/main/Generating_Dog_Images_with_Autoencoders.ipynb)

## Abstract
Generative models, particularly Variational Autoencoders (VAE), can capture complex data distributions and generate new samples. In this project we implement a Convolutional Autoencoder (CAE) and a Variational Autoencoder (VAE) to model a dataset of real-world dog images. The CAE is used as a foundation for reconstruction tasks; the VAE is then trained to generate novel dog images.

Model evaluation includes reconstruction loss, Inception Score and Fréchet Inception Distance (FID). Results show that the CAE performs well at reconstruction but cannot generate meaningful samples, while the VAE can produce new images with some structural fidelity. However, generated images exhibit blurring and relatively high FID scores — they do not look fully realistic but are an improvement over the CAE.

