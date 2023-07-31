# Generate Synthetic Images with DCGANs in Tensorflow

This repository contains a Jupyter Notebook (`DCGAN_fashion-mnist.ipynb`) that demonstrates the implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) in TensorFlow. The DCGAN model is used to generate synthetic images of fashion items based on the Fashion-MNIST dataset.

## Project Overview

The goal of this project is to implement the DCGAN architecture introduced in the paper "Unsupervised representation learning with deep convolutional generative adversarial networks" by Radford, Alec et al. The DCGAN is a powerful generative model that can learn to generate realistic synthetic images.

The project follows the following key steps:

1. Load and preprocess the Fashion-MNIST dataset.
2. Create batches of training data for efficient training.
3. Build the generator network for DCGAN, responsible for generating synthetic images.
4. Build the discriminator network for DCGAN, responsible for distinguishing between real and synthetic images.
5. Compile the DCGAN model by combining the generator and discriminator networks.
6. Define the training procedure for DCGAN, using adversarial training with the generator and discriminator.
7. Train the DCGAN on the Fashion-MNIST dataset to generate synthetic fashion item images.
8. Generate and save synthetic images at different epochs during training.
9. Create an animated GIF to visualize the progress of image generation during training.

## Requirements

The implementation requires TensorFlow and matplotlib libraries. Make sure to have them installed before running the notebook.

## How to Use the Notebook

To use this notebook, run each cell sequentially. The notebook will guide you through the project, showing the dataset, building the generator and discriminator networks, training the DCGAN, and generating synthetic images.

Feel free to experiment with the hyperparameters, architecture, and other settings to explore the model's performance and the quality of generated images.

Please note that the training process may take some time, depending on your hardware and the number of epochs you choose. It is recommended to run this notebook on a machine with a GPU for faster training.

![dcgan](https://github.com/ozzmanmuhammad/DCGAN/assets/93766242/7181b32f-40ee-4f97-a691-99ed8ab0135e)


## Acknowledgments

This project is based on the DCGAN architecture proposed by Radford, Alec et al. in their paper "Unsupervised representation learning with deep convolutional generative adversarial networks" (ICLR 2016).

The Fashion-MNIST dataset is used in this project, and it was originally created by Zalando Research (MIT License). It consists of 28x28 grayscale images of 10 different fashion categories.

If you have any questions or suggestions, feel free to reach out to the author.

Happy image generation with DCGANs!
