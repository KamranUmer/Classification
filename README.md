<div align="center">

# 🐱 Dog vs Cat Classification

**99% accurate dog-vs-cat image classifier using transfer learning with TensorFlow Hub.**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">

<a href="https://colab.research.google.com/github/KamranUmer/Classification/blob/main/DogVsCat.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a>

</div>

<p align="center"><img src="https://github.com/KamranUmer/DogVsCat/assets/86089489/d42fa4bd-068e-41b3-a9db-6bc183b22f23" alt="Dog vs Cat Classification screenshot" width="85%"></p>

## 📌 Overview

Classifies photos as dog or cat by reusing a pre-trained image model from TensorFlow Hub and training only a small classification head, which reaches high accuracy in just 5 epochs.

## 🔬 Pipeline

- Resize images and convert them to NumPy arrays
- Train/test split and pixel scaling
- Pre-trained MobileNetV2 feature extractor from TensorFlow Hub + dense output layer
- Adam optimiser, 5 epochs
- Predictive system for new images

## 📊 Results

| Metric | Value |
|---|---|
| Test accuracy | **99.0%** |
| Test loss | 0.042 |

## 🚀 Getting Started

```bash
# Open the notebook in Google Colab (badge above), choose a GPU runtime,
# then run the cells from top to bottom.
```

---

<div align="center">

Built by <a href="https://github.com/KamranUmer"><b>Kamran Umer</b></a> · ⭐ Star the repo if you find it useful

</div>
