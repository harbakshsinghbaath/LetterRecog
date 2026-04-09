# MNIST & Fashion-MNIST Practice in PyTorch

This repository contains my experiments and practice notebooks for building, training, and evaluating neural networks on the **MNIST** and **Fashion-MNIST** datasets using PyTorch.  
The goal was to strengthen my understanding of dataset handling, model design, training loops, and evaluation workflows in PyTorch.

---

## 📚 Datasets
- **MNIST**: Handwritten digits (0–9), grayscale images of size 28x28.
- **Fashion-MNIST**: Clothing items (10 categories), grayscale images of size 28x28.

Both datasets are widely used for benchmarking image classification models.

---

## 🛠️ What I Practiced
- Loading datasets from CSV and torchvision.
- Creating a custom `Dataset` class and wrapping it with `DataLoader`.
- Normalizing image data and handling labels correctly.
- Building simple feedforward neural networks with `nn.Module`.
- Training loops with forward pass, loss calculation, backward pass, and optimizer step.
- Evaluating models on test sets and computing accuracy.
- Understanding underfitting vs overfitting through experiments.

---

## 📂 Repository Structure
- `Neurals.ipynb` → Practice notebook for MNIST digits.
- `fashion.ipynb` → Practice notebook for Fashion-MNIST.
- `README.md` → Project documentation.

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/harbakshsinghbaath/LetterRecog.git
   cd LetterRecog
