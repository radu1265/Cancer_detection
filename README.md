# Brain cancer detection

# Brain Tumor Detection using Deep Learning

This project explores two deep learning approaches for classifying brain MRI scans as cancerous or healthy. It compares a classic **LeNet** model trained from scratch with a **fine-tuned ResNet-50** pretrained on ImageNet. The main focus is on data preprocessing, augmentation, and visualization to improve performance on a limited dataset.

---

## 🧩 Project Overview
The notebook demonstrates:
- Loading and preparing MRI images from a Kaggle dataset.
- Applying preprocessing and data augmentation using **MONAI** transforms.
- Building and training two CNN architectures:
  - **LeNet** — a simple custom network for baseline performance.
  - **ResNet-50** — fine-tuned for transfer learning.
- Evaluating both models using **ROC-AUC**, **classification reports**, and visual comparison of results.

---

## 🧰 Technologies Used
- **Python**
- **PyTorch**
- **MONAI**
- **Matplotlib**
- **scikit-learn**
- **PIL**

---

## ⚙️ Key Features
- Robust data augmentation (random flips, rotations, zooms, and scaling).
- Visualization of input data and model predictions.
- Deterministic training setup for reproducibility.
- Side-by-side comparison of LeNet vs ResNet architectures.
- Transfer learning implementation for small dataset scenarios.

---

## 🚀 Results
The project highlights the performance difference between custom and pretrained CNNs on a small medical dataset, showing the effectiveness of transfer learning in improving model generalization and accuracy.
