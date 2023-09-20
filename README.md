# DCGANs for Fashion-MNIST

This project trains and visualizes the outputs of a simple Deep Convolutional GAN (DCGAN) to generate realistic-looking (but fake) images of clothing.

## Goal

The goal of this project is to learn how to implement and train a DCGAN using TensorFlow 2 / Keras.

[!](https://github.com/mahidavedant/DCGANs-Fashion-generation/blob/main/fashion-dcgan.gif)

## Data

The data used for this project is the `Fashion-MNIST` dataset, which consists of 60,000 training images and 10,000 test images of 10 different classes of clothing items. The images are grayscale and have a size of `28 x 28 pixels`.

## Code

The code for this project is written in Python and uses TensorFlow 2 / Keras as the main framework for building and training the DCGAN model. The code is organized in a Jupyter notebook called `Generate_Fashion_with_GANs.ipynb`, which contains the following sections:

- Importing libraries and modules
- Downloading, Loading and preprocessing the data
- Defining the generator and discriminator models
- Defining the loss functions and optimizers
- Defining the training loop and helper functions
- Training the DCGAN model
- Visualizing the generated images
- Saving the images and Generate GIF

## Results

The DCGAN model was trained for 100 epochs on a GPU. The intermediate images generated by the generator were displayed after every epochs. The final result is a GIF animation that shows the evolution of the generated images over time. The GIF animation and generated images can be found in the `fashion-dcgan.gif` and `generated` folder respectively.


## How to run

To run this project, you need to have Python 3 and TensorFlow 2 installed on your machine. You also need to have Jupyter Notebook or Jupyter Lab installed to open and run the notebook. You can clone this repository using git or download it as a zip file.


