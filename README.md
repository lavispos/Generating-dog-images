# Generating Dog Images with Autoencoders
**Author:** Lavinia Sposetti - Thang Dinh  
**Year:** 2024

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lavispos/Generating-dog-images/blob/main/Generating_Dog_Images_with_Autoencoders.ipynb)  

## Abstract
Generative models, particularly variational autoencoders (VAE), have shown to be able to capture highly complex data distributions and generate new samples from them. In this work, we implement a VAE to model the distribution of a set of dog images originating from real-world scenarios.

We aim to use the VAE to generate new dog images. As a foundation, we first design and train a convolutional autoencoder (CAE) to efficiently reconstruct samples from the dataset. Building upon this foundation, we implement the VAE. Model performance is evaluated using reconstruction loss, Inception Score and Fréchet Inception Distance (FID), assessing reconstruction and image generation capabilities. Our final results show that while CAE excels in reconstruction, it cannot generate anything meaningful. The VAE successfully generates new samples with some structural fidelity, although challenges such as blurring and high FID scores highlight areas for improvement. The generated images do not look like realistic dogs, but provide significant improvement over the CAE.
