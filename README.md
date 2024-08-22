# CVAE
Text-to-Image Generation with Conditional Variational Autoencoder (CVAE)

**Overview**
This project implements a Conditional Variational Autoencoder (CVAE) for generating images based on specific conditions, such as digit classes. The model is trained using the MNIST dataset, a widely recognized dataset of handwritten digits, and demonstrates the ability to generate new images that match the specified conditions.

**Project Structure**
- main.py: The main script that orchestrates the entire workflow, including data loading, model training, and image generation.
- mnist.py: Contains utilities for loading and preprocessing the MNIST dataset, such as normalizing the data and creating data batches.
- condvae.py: Defines the Conditional Variational Autoencoder (CVAE) model architecture, including the encoder, decoder, and the loss function used during training.

**Features**
- Data Loading and Preprocessing: Efficient loading and normalization of the MNIST dataset to prepare it for training.
- Conditional Image Generation: The CVAE model can generate images that match specified conditions (e.g., generating a digit '7').
- Scalable Architecture: The model architecture is modular, allowing for easy adaptation to other datasets or conditions beyond digit classes.

**Requirements:**
- Python 3.x
- TensorFlow or PyTorch (depending on which framework you used)
- NumPy
- Matplotlib (for visualizing generated images)
- Any other dependencies specified in your environment (e.g., requirements.txt)


This project implements a Conditional Variational Autoencoder (CVAE) for generating images based on specific conditions, such as digit classes. The model is trained using the MNIST dataset, a widely recognized dataset of handwritten digits, and demonstrates the ability to generate new images that match the specified conditions.
