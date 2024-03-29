# Generative Adversarial Network (GAN) Project

This project implements a basic Generative Adversarial Network (GAN) using PyTorch and applies it to the MNIST dataset for generating hand-written digits.

## Overview

This repository contains code for training a GAN to generate realistic hand-written digit images resembling those from the MNIST dataset. The GAN consists of a generator and a discriminator, both implemented using PyTorch.

## How it Works

The project follows these main steps:

1. **Data Loading**: The MNIST dataset is loaded using PyTorch's DataLoader, which provides batches of hand-written digit images.

2. **Generator and Discriminator**: The GAN architecture comprises a generator and a discriminator. The generator generates fake images, while the discriminator tries to distinguish between real and fake images.

3. **Training Loop**: The training loop consists of alternating optimization steps for the generator and discriminator. The generator aims to generate images that are realistic enough to fool the discriminator, while the discriminator aims to correctly classify real and fake images.

4. **Loss Calculation**: The loss functions for the generator and discriminator are calculated using binary cross-entropy loss with logits.

5. **Visualization**: During training, sample images generated by the generator are visualized to monitor the training progress.

## Requirements

- Python 3.x
- PyTorch
- torchvision
- tqdm
- matplotlib

## Usage

To train the GAN model, Clone this repository:


Results: 

## Results

After training, the GAN model is capable of generating realistic hand-written digit images resembling those from the MNIST dataset.

## References

- [Generative Adversarial Networks (GANs)](https://en.wikipedia.org/wiki/Generative_adversarial_network)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)

## Author
Aryan Rajpurkar

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
