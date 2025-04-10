# 🧠 VGGNet Implementation in PyTorch (Colab-Ready)

This repository contains a simplified and easy-to-follow PyTorch implementation of **VGG16**, one of the most influential deep learning architectures in computer vision.

> 📚 Inspired by the 2014 paper [“Very Deep Convolutional Networks for Large-Scale Image Recognition”](https://arxiv.org/abs/1409.1556) by Simonyan & Zisserman.

---

## 🚀 Features

- Full VGG16 model built from scratch using PyTorch
- Trained on **CIFAR-10** dataset
- Compatible with **Google Colab** and GPU acceleration
- Includes:
  - Data preprocessing & augmentation
  - Training & evaluation loops
  - Progress bar with `tqdm`
  - Dropout & regularization

---

## 🧪 Dataset

This notebook uses **CIFAR-10**, a standard benchmark dataset consisting of 60,000 32x32 color images in 10 classes (e.g., airplane, cat, ship, etc.).

---

## 📦 Requirements

- Python 3.x
- PyTorch
- torchvision
- tqdm

Install with:

```bash
pip install torch torchvision tqdm
