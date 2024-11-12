# Anime Image Generation with GANs

This project utilizes a **Generative Adversarial Network (GAN)** to generate high-quality **anime-style images**. By training on a dataset of 63,000+ anime images, the model learns to synthesize new, realistic anime characters. This repository includes code for data preprocessing, model architecture, training, and visualizing the results, with a GIF showing the progression of generated images.

---

## 📚 Project Overview

Generative Adversarial Networks (GANs) are powerful deep learning models that consist of two components: a **Generator** and a **Discriminator**. The Generator creates synthetic images, while the Discriminator attempts to distinguish between real and generated images. Through adversarial training, both networks improve over time, allowing the Generator to produce high-quality, realistic images.

This project applies GANs to the task of generating anime-style images, training the model on a large dataset of anime images, and leveraging the power of deep learning to create completely new, high-quality anime characters.

---

## 🔧 Technologies & Libraries Used

- **TensorFlow** & **Keras**: For building and training the GAN model.
- **NumPy**: For data manipulation and handling image arrays.
- **Pillow (PIL)**: For image preprocessing and resizing.
- **Matplotlib**: For visualizations and plotting training results.
- **imageio**: To create a GIF that showcases the model's training progression.

---

## 🖼️ Dataset

The dataset used in this project consists of **63,565 anime images**. These images depict a wide variety of anime styles and characters. The images are resized to 64x64 pixels and normalized for efficient model training.

- **Dataset Source**: Kaggle (Dataset Name: **GAN Project**)

---

## 🛠️ Project Structure

```plaintext
├── data/                     # Preprocessed image dataset
├── model/                    # GAN model architecture (Generator & Discriminator)
├── training/                 # Training script and log files
├── results/                  # Generated images and training progress GIF
├── README.md                 # Project overview and instructions
└── requirements.txt          # Project dependencies
