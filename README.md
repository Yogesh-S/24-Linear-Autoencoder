# Linear-Autoencoder

Let us start off by building a simple autoencoder to compress the MNIST dataset. With autoencoders, we pass input data through an encoder that makes a compressed representation of the input. Then, this representation is passed through a decoder to reconstruct the input data. Generally the encoder and decoder will be built with neural networks, then trained on example data.

![alt text](https://github.com/Yogesh-S/24-Linear-Autoencoder/blob/main/autoencoder_1.png?raw=true)

### Compressed Representation

A compressed representation can be great for saving and sharing any kind of data in a way that is more efficient than storing raw data. In practice, the compressed representation often holds key information about an input image and we can use it for denoising images or oher kinds of reconstruction and transformation!


![alt text](https://github.com/Yogesh-S/24-Linear-Autoencoder/blob/main/denoising.png?raw=true)

In this notebook, we'll be build a simple network architecture for the encoder and decoder.
