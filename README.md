# Human Action Recognition using CNN + LSTM  
*SEECS NUST – Deep Learning Internship Project*  

This repository contains the work completed during my **CNN Internship at SEECS, NUST**, focused on building deep learning models for **Human Action Recognition (HAR)** from video sequences.  
The project explores multiple deep architectures including **ConvLSTM** and **LRCN (Long-term Recurrent Convolutional Network)** using the **UBFC dataset**.  

---

## Project Objective  
To build and evaluate deep learning architectures for **classifying human actions from video** using frame sequences, achieving robust temporal understanding and generalization.

The project focuses on:

- Video preprocessing & frame extraction  
- CNN-based spatial feature learning  
- LSTM/ConvLSTM-based temporal modeling  
- Performance comparison between models  

---

## Dataset: UBFC Video Dataset  

The project uses the **UBFC** dataset, containing video samples labeled with different human actions.  
Each video is decomposed into frames and processed as a sequence for temporal deep learning models.

---

# Approaches Implemented  

The `Human_Action_Recogntion_using_CNN_+_LSTM.ipynb.ipynb` contains the complete workflow, organized in the following steps:

---

## **Step 1 — Visualizing Data & Labels**  
Sample video frames were extracted and plotted to understand action categories and dataset quality.

---

## **Step 2 — Dataset Preprocessing**

- Frame extraction  
- Resizing & normalization  
- Sequence generation  
- Label encoding  
- Data augmentation (when applicable)

---

## **Step 3 — Train/Test Split**  
Data was split ensuring balanced representation of all action categories.

---

# **Deep Learning Architectures**

## **Step 4 — ConvLSTM Approach**

### **4.1 — Construct Model**
A hybrid network combining:  
- Convolutional layers for spatial feature extraction  
- LSTM layers for temporal sequence learning  
- Dense layers for classification

### **4.2 — Compile & Train**  
Model trained on sequences with appropriate loss, optimizer, and metrics.

### **4.3 — Loss & Accuracy Curves**  
Plotting training & validation curves to evaluate convergence and overfitting.

---

## **Step 5 — LRCN (Long-term Recurrent Convolutional Network)**

### **5.1 — Construct Model**
Uses:  
- A CNN (per-frame feature extractor)  
- Followed by LSTMs to learn temporal evolution  
- Fully-connected layers for classification  

### **5.2 — Compile & Train**  
Comparative analysis with ConvLSTM.

### **5.3 — Loss & Accuracy Curves**  
Used for selecting the best-performing architecture.

---

# **Step 6 — Testing on YouTube Videos**

The best model was evaluated on real-world YouTube videos (after preprocessing):

- Frame extraction  
- Sequence generation  
- Action prediction  

This demonstrates model generalization beyond the UBFC dataset.

---

# Results Summary  
(Detailed plots inside notebooks)

- Both ConvLSTM and LRCN successfully learned temporal patterns  
- LRCN generally showed smoother convergence due to decoupled CNN extraction  
- The best model showed strong performance on both test data and YouTube videos  
- Action classes with higher motion variation performed better  

---

# Author

**Muhammad Sarmad Sohail**
Data Engineer | Machine Learning Engineer  
SEECS NUST – CNN Internship  

GitHub: [https://github.com/msarmadsohail](https://github.com/msarmadsohail)  
LinkedIn: [https://linkedin.com/in/msarmadsohail](https://linkedin.com/in/msarmadsohail)  

```
