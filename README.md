# American Sign Language

# Overview
This notebook applies a convolutional neural network to classify a dataset of American Sign Language alphabet images. The model has 20 layers and was able to classify the images with an accuracy of 100%. This notebook is hosted on Kaggle and can be found here: https://www.kaggle.com/code/jarredpriester/sign-language-mnist-cnn-accuracy-100/notebook

# Purpose of the Project
The purpose of the project was to learn how to use a CNN to classify sign language images, and hopfully one day be able to create an app that can detect sign language in live videos.

# What Did I Learn
I learned about the max pooling 2D layer in Keras. This layer downsamples the input along its height and width by taking the max value over an input window for each channel of the input.

# Dataset Used
The dataset consists of 27,455 training images and 7,172 test images. Each image is grayscaled and has a 28 x 28 pixel structure. Each image includes the label of which letter in the alphabet the image represents. There are 24 letters in this dataset, 'j' and 'z' are not included because they both involve motion. This dataset was found on Kaggle.

# Files Used
sign-language-mnist-cnn-accuracy-100.ipynb - python notebook
