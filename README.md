# Human Action Recognition using CNN-LSTM

[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.x-red.svg)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 🎯 Project Overview

Deep learning models for **Human Action Recognition (HAR)** from video sequences using the **UBFC dataset**.

**Developed during:** CNN Internship at SEECS, NUST (Jun - Aug 2023)

This project explores multiple deep architectures including **ConvLSTM** and **LRCN (Long-term Recurrent Convolutional Network)** for temporal video understanding.

---

## 📋 Objectives

- Video preprocessing & frame extraction
- CNN-based spatial feature learning
- LSTM/ConvLSTM-based temporal modeling
- Performance comparison between architectures

---

## 📊 Dataset

**UBFC Video Dataset** - Labeled human action video samples decomposed into frame sequences for temporal deep learning models.

---

## 🏗️ Architectures Implemented

### **1. ConvLSTM**
Hybrid network combining:
- Convolutional layers for spatial feature extraction
- LSTM layers for temporal sequence learning
- Dense layers for classification

### **2. LRCN (Long-term Recurrent Convolutional Network)**
- CNN per-frame feature extractor
- LSTM layers for temporal evolution
- Fully-connected layers for classification

---

## 📁 Repository Structure

```
├── exploratory_notebooks/        # Initial data exploration
├── implementation_1/             # First architecture attempt
├── implementation_2/             # Improved model + training logs
├── implementation_3/             # Final optimizations
├── Human_Action_Recognition_using_CNN_+_LSTM.ipynb  # Complete workflow
├── LICENSE
└── README.md
```

---

## 🚀 Workflow

**Step 1:** Visualizing Data & Labels  
**Step 2:** Dataset Preprocessing (frame extraction, resizing, augmentation)  
**Step 3:** Train/Test Split  
**Step 4:** ConvLSTM Model (construct, train, evaluate)  
**Step 5:** LRCN Model (construct, train, compare)  
**Step 6:** Testing on YouTube Videos (real-world generalization)

---

## 📊 Results Summary

✅ Both ConvLSTM and LRCN successfully learned temporal patterns  
✅ LRCN showed smoother convergence (decoupled CNN extraction)  
✅ Strong performance on test data and YouTube videos  
✅ Action classes with higher motion variation performed better

---

## 🛠️ Tech Stack

- **Language:** Python 3.8+
- **Frameworks:** PyTorch, Keras, TensorFlow
- **Libraries:** NumPy, Matplotlib, OpenCV
- **Dataset:** UBFC (Human Action Recognition)

---

## 👨‍💻 Author

**Muhammad Sarmad Sohail**  
Data Engineer | Machine Learning Engineer  
Research Intern | SEECS, NUST

msarmadsohail@gmail.com  
[LinkedIn](https://linkedin.com/in/msarmadsohail) | [GitHub](https://github.com/msarmadsohail) | [Portfolio](https://msarmadsohail.github.io)

---

## 📝 License

MIT License - see [LICENSE](LICENSE) file
