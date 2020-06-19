# Image-Denoising-using-Autoencoder

Removing noise from images of Fashion MNIST Dataset using Autoencoder.

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels (see above), and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.

To locate a pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27. The pixel is located on row i and column j of a 28 x 28 matrix.

For example, pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top

Labels

Each training and test example is assigned to one of the following labels:

0: T-shirt/top 1: Trouser 2: Pullover 3: Dress 4: Coat 5: Sandal 6: Shirt 7: Sneaker 8: Bag 9: Ankle boot

## Source

https://github.com/zalandoresearch/fashion-mnist

It is included in tensorflow.datasets

You can import it directly using tensorflow.

## Project Overview:

1- Exploratory Data Analysis

2- Normalization and Addition of Noise

3- Convolutional Neural Network - CNN

4- Predictions and Conclusion
