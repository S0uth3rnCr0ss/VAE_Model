# Variational Autoencoder (VAE) for MNIST  

This repository contains a **Variational Autoencoder (VAE) implementation** using PyTorch. The VAE learns to encode MNIST handwritten digits into a **latent space** and reconstruct them, while also being able to generate new digits from random samples.

---

## 🚀 **Project Overview**
- Uses **Encoder-Decoder architecture** to learn a compact representation of MNIST images.
- Implements the **Reparameterization Trick** to allow backpropagation through the latent space.
- Trained using a combination of **Binary Cross-Entropy (BCE) Loss** and **KL Divergence**.
- Capable of **reconstructing input images** and **generating new images** from random latent vectors.

---

## 📂 **Project Structure**
