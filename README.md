# Kannada-Mnist

This is a machine learning project using Deep Neural Networks (DNNs) and Convolutional Neural Networks (CNNs) with Keras, and more specifically, and it is about a classification problem for the prediction of hand-written digits. 
## Source
The dataset used is an alternative one with regard to the popular [MNIST digits](https://conx.readthedocs.io/en/latest/MNIST.html) dataset, and the project was constructed in the context of a [kaggle class competition](https://www.kaggle.com/c/cs98x-kannada-mnist) (module CS985 Machine Learning) at Strathclyde University, academic year 2019-20.

["Kannada"](https://en.wikipedia.org/wiki/Kannada) is a language spoken predominantly by people of Karnataka in southwestern India. The language has roughly 45 million native speakers and is written using the Kannada script

The format is similar to MNIST in terms of how the data is structured.
## Description
A range of deep neural network architectures and techniques are applied with the final goal of finding the optimal model for the digits' predictions.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive, and each pixel column in the training set has a name like pixel{x}, where x is an integer between 0 and 783, inclusive. Overall, there are 10 classes since the handwritten digits range from 0 to 9.
## Purpose
The classification of the images of hand-written digits, and the prediction of those numbers.
## Environment
Google colab with GPU
## Acknowledgments
The project uses part of data that was published in: Prabhu, Vinay Uday. "Kannada-MNIST: A new handwritten digits dataset for the Kannada language." arXiv preprint arXiv:1908.01242 (2019).
