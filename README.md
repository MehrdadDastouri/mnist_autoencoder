# Autoencoder for MNIST using PyTorch

"This project demonstrates how to build and train an Autoencoder using PyTorch to reconstruct images from the MNIST dataset. The Autoencoder compresses the input into a smaller representation (encoding) and then reconstructs the original input from this compressed representation (decoding)."

Features:
  - Implements an Autoencoder model with:
      - Encoder: Compresses 28x28 images into a latent space of size 32 using fully connected layers with ReLU activation.
      - Decoder: Reconstructs images from the latent space using fully connected layers with Tanh activation.
  - Trains the model on the MNIST dataset using:
      - Mean Squared Error (MSE) loss function for measuring reconstruction quality.
      - Adam optimizer for efficient training.
  - Visualizes:
      - The training loss over epochs.
      - Original and reconstructed images side by side for comparison.
