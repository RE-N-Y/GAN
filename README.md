# GAN

## Keras Generative Adversarial Model

MNIST data generation through GAN. The following repository is a keras implementation of GAN model for MNIST data generation from noise.
An additional research I conducted is feeding MNIST data as a noise after training to examine if the content of the noise can somehow
provide a 'hint' to the generator on which type of data to generate. The **gan_mnist_supervised** notebook works to examine how we can
directly feed in labels to generate MNIST data given a certain label.
Note that full example are hosted on google colab on the link below.

###Colab notebook links
-gan_mnist: https://drive.google.com/open?id=1Rzk1j0Pirc4bLmbbDOGhyZ8nyZ7EzeMi
-gan_mnist_supervised: https://drive.google.com/open?id=1HdoRvYCYaPxrKGIlbSzTrVsTY64Bwh3t
