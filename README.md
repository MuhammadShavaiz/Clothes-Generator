# Clothes-Generator

The Clothes-Generator project aims to generate clothing images using Generative Adversarial Networks (GANs). The model is trained on the Fashion MNIST dataset and implemented using TensorFlow. Currently, the project is in progress, with training incomplete and results not yet satisfactory.

## Overview

This project uses GANs to create synthetic clothing images by training on the Fashion MNIST dataset. The GAN architecture includes a generator and a discriminator, where the generator creates images and the discriminator evaluates them. The model is trained to improve both components iteratively.

## Dataset

The model is trained using the Fashion MNIST dataset, which contains grayscale images of various clothing items:

- **Dataset Size:** 60,000 training images and 10,000 test images
- **Image Size:** 28x28 pixels
- **Classes:** 10 (e.g., T-shirts, trousers, dresses, etc.)

## Architecture

- **Generator:** Creates synthetic clothing images from random noise.
- **Discriminator:** Evaluates the authenticity of the generated images and provides feedback to the generator.

## Current Status

- **Epochs Trained:** 10
- **Discriminator Loss:** 0.6307
- **Generator Loss:** 0.6626

The results are not yet satisfactory, and the training process needs further refinement.

## Technologies Used

- **TensorFlow:** Framework for building and training the GAN model.
- **Keras:** High-level API used within TensorFlow for defining the model.
- **Fashion MNIST Dataset:** Dataset used for training and evaluating the model.
- **Python:** Programming language for implementing the project.

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/MuhammadShavaiz/Clothes-Generator.git
```

## Usage

**Prepare the Dataset:**

Ensure the Fashion MNIST dataset is properly downloaded and accessible. You can use TensorFlow’s built-in methods to load the dataset.

**Train the Model:**

To begin training the model, run the training function in the Jupyter notebook. Ensure you set the desired number of epochs and any other necessary parameters before execution. This will start the training process and save the generated images at each epoch.

**Evaluate and Generate Images:**

After training, run the evaluation functions in the Jupyter notebook to generate and view clothing images. Make sure to follow any necessary steps or configurations before executing the functions. This will allow you to visualize the results of the generated images.

## Future Work

- Continue training the GAN for more epochs to improve the quality of generated images.
- Fine-tune hyperparameters and model architecture to enhance performance.
- Implement additional evaluation metrics to assess image quality.

## Contact

For any questions or contributions, please reach out to:

Muhammad Shavaiz Butt - [shavaizsohail@gmail.com](mailto:shavaizsohail@gmail.com)
