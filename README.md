# GAN Models on CIFAR10 Dataset Using PyTorch

This repository contains the implementation of Generative Adversarial Networks (GANs) trained on the CIFAR10 dataset using PyTorch.

## Overview

The project uses GANs, a class of machine learning frameworks designed to generate new content. In this case, we're generating images that resemble the ones found in the CIFAR10 dataset. The GAN model consists of two parts: a Generator and a Discriminator. The Generator creates new images, and the Discriminator evaluates them. The two parts are trained together with the goal of improving the Generator's ability to create realistic images.

## Requirements

This project uses Python 3.8 and the following libraries:

- PyTorch
- torchvision
- NumPy
- Matplotlib

You can install the required packages using pip:

```bash
pip install -r requirements.txt