# Variational Autoencoder to Generate Clothing

Project uses Python, Jupyter Notebook, and Tensorflow to generate images of common clothing items (shoes, sweaters, etc.). Dataset taken from

```python
keras.datasets.fashion_mnist
```

# Models Used
This project uses a Variational Autoencoder trained on the dataset of clothing to generate random and entirely new images of clothing. 

The program then uses a denoising Autoencoder, trained to reconstruct images from altered "noisy" training images, to increase the image definition of the generated images.