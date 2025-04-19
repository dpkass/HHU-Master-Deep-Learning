# HHU Master Deep Learning

This repository contains exercises and implementations from the **Deep Learning** course at Heinrich Heine University (HHU), taught in the **Winter Semester 2024/25**. The course progresses from foundational topics like automatic differentiation to advanced deep learning systems such as transformers and challenge-driven applications.

---

## 📌 Course Overview

The course consists of 13 programming assignments, each with focused objectives ranging from low-level tensor operations to high-level sequence modeling. Each folder includes the necessary notebooks, data, and helper code to reproduce the solutions.

---

## 📂 Repository Structure

```
Exercises
├── Assignment 01 → Autodiff puzzles and Jacobians
├── Assignment 02 → Mini-batch MLP regressor (GPA → IQ)
├── Assignment 03 → GeLU, Leaky-ReLU, einsum with backprop
├── Assignment 04 → Random/Grid CV with Fashion-MNIST
├── Assignment 05 → Custom CNN layers (Conv2D, ConvT)
├── Assignment 06 → Inception modules (GoogLeNet-style)
├── Assignment 07 → Normalization, Focal Loss
├── Assignment 08 → ResNet with stochastic depth & augmentation
├── Assignment 09 → CIFAR-10 competition challenge
├── Assignment 10 → Character-level next-token prediction
├── Assignment 11 → BPE tokenizer implementation
├── Assignment 12 → Transformer for hate speech detection
└── Assignment 13 → GPTrump: leaderboard challenge submission
```

---

## ⚙️ Installation & Setup

```bash
pip install -r requirements.txt
```

---

## 📊 Results Highlights

| Assignment              | Metric                | Achieved     |
|-------------------------|-----------------------|--------------|
| 07 – Normalization      | Fashion‑MNIST val acc | **86.8 %**   |
| 08 – ResNet + Aug       | Fashion‑MNIST val acc | **76.5 %**   |
| 09 – CIFAR‑10 Challenge | Test accuracy         | **67.3 %**   |
| 12 – Hate Speech        | Test accuracy         | **79.6 %**   |
| 13 – GPTrump            | Final perplexity      | **2.48**     |
```
