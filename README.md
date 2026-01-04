# 🧠 GAN Image Generator (CIFAR-10)

This project implements a **Generative Adversarial Network (GAN)** trained on the **CIFAR-10 dataset** using **PyTorch** and **Google Colab**.  
The model learns to generate realistic-looking images by training a generator and discriminator in an adversarial setup.

---

## 🚀 Project Overview

- **Model Type:** Deep Convolutional GAN (DCGAN)
- **Dataset:** CIFAR-10 (60,000 images, 10 classes)
- **Framework:** PyTorch
- **Training Environment:** Google Colab (CUDA-enabled GPU)
- **Output:** Synthetic images generated from random noise

This project is an educational and experimental step toward building **scalable generative AI systems**.

---

## 🖼 Sample Results

During training, the model periodically generates images to visualize learning progress.  
From later epochs, generated images begin to resemble real CIFAR-10 objects such as animals and vehicles.

---

## 🧪 How It Works (Simple Explanation)

A GAN consists of two neural networks:

- **Generator (G):** Creates fake images from random noise
- **Discriminator (D):** Tries to distinguish real images from fake ones

Both networks compete, and over time the generator improves its ability to create realistic images.

---

## ▶️ How to Run (Google Colab)

1. Open the notebook in Google Colab  
2. Enable GPU:
   - Runtime → Change runtime type → GPU
3. Run all cells to:
   - Download CIFAR-10
   - Train the GAN
   - Generate sample images

---

## 📓 Notebook

- `GAN_Image_Generator.ipynb` — full training and generation pipeline

---

## 🔮 Future Improvements

- Conditional GAN (class-controlled generation)
- WGAN-GP for more stable training
- Model checkpointing & image saving
- Inference API for real-world usage
- Deployment with Docker & cloud platforms

---

## 📌 Author

**Gyang Emmanuel**  
Exploring Generative AI, deep learning, and scalable AI systems.

---

## 📜 License

This project is open-source and available for educational and research purposes.
