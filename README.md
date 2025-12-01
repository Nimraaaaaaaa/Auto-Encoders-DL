MNIST Autoencoders – Vanilla, Convolutional, Denoising & Variational

This project demonstrates four different types of Autoencoders built and trained on the MNIST handwritten digits dataset. Each model learns compressed latent representations and reconstructs input images, showcasing the power of neural compression and generative modeling.

🚀 Autoencoders Implemented
Vanilla Autoencoder

Simple fully-connected encoder–decoder architecture for basic dimensionality reduction and reconstruction.

 Convolutional Autoencoder

Uses Conv2D & Conv2DTranspose layers for improved spatial feature extraction and cleaner reconstructions.

 Denoising Autoencoder

Learns to remove noise from corrupted MNIST images, improving robustness and feature learning.

 Variational Autoencoder (VAE)

A probabilistic generative model that learns latent distributions and can generate new digit samples.

📂 Notebook Contents

MNIST dataset loading & preprocessing

Architecture design for each Autoencoder

Training loops & loss visualization

Image reconstruction results

Noise addition for Denoising Autoencoder

Latent space sampling (for VAE)

🧠 Skills Demonstrated

Deep Learning (Keras / TensorFlow)

Convolutional architectures

Generative modeling

Latent space learning

Image reconstruction & visualization

MNIST preprocessing techniques

▶️ How to Run

Install required packages:

pip install tensorflow numpy matplotlib


Open the notebook:

jupyter notebook Types_of_autoencoders_MNISt.ipynb


Run all cells to train and visualize Autoencoders.

📸 Outputs

Reconstructed MNIST digits

Noisy vs cleaned images

VAE-generated samples

Training loss curves

📘 File Included
Types_of_autoencoders_MNISt.ipynb   # Main notebook with all models
