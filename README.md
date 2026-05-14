# Facial Expression Recognition using Deep Learning (VGG16)

## 📌 Project Overview

This project focuses on **Facial Expression Recognition** using Deep Learning techniques, specifically the **VGG16 Convolutional Neural Network (CNN)** architecture.

The system is designed to analyze facial expressions and associate them with psychological traits using image-based learning models. The project also explores explainable AI concepts through manifold visualization techniques such as **UMAP** and **t-SNE**.

This work was completed as part of an internship at **Indian Institute of Information Technology Kottayam (IIIT Kottayam)**.

---

## 🧠 Objectives

- Detect and classify human facial expressions
- Train a deep learning model using facial image datasets
- Improve understanding of how neural networks process facial data
- Visualize learned facial representations using manifold learning techniques
- Explore AI explainability in psychology and human-computer interaction

---

## 🚀 Features

- Facial expression classification using CNN
- Pretrained VGG16 model implementation
- Image preprocessing and augmentation
- High accuracy prediction system
- Confusion matrix visualization
- UMAP and t-SNE manifold visualizations
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| TensorFlow / Keras | Deep Learning Framework |
| OpenCV | Image Processing |
| NumPy | Numerical Operations |
| Pandas | Data Handling |
| Matplotlib | Data Visualization |
| Scikit-learn | Evaluation Metrics |
| Jupyter Notebook | Model Training & Experiments |

---

## 🧬 Model Architecture

The project uses the **VGG16 CNN Architecture**.

### Why VGG16?
- Deep architecture with 16 layers
- Excellent feature extraction capability
- High accuracy in image classification tasks
- Effective for facial expression recognition

---

## 📂 Dataset

The dataset contains facial expression images representing multiple emotions such as:

- Happy
- Sad
- Angry
- Fear
- Surprise
- Neutral
- Disgust
- Contempt

Images are preprocessed before training:
- Resizing
- Normalization
- Data augmentation

---

## ⚙️ Methodology

### 1. Data Collection
Collected facial expression datasets containing multiple emotions and psychological characteristics.

### 2. Data Preprocessing
- Image resizing
- Noise removal
- Normalization
- Data augmentation

### 3. Model Training
The VGG16 model is trained on facial expression images.

### 4. Performance Evaluation
Metrics used:
- Accuracy
- Precision
- Recall
- F1-score

### 5. Explainability & Visualization
Used:
- UMAP Visualization
- t-SNE Visualization

to understand how the model learns facial features internally.

---

## 📊 Results

| Model | Accuracy | Precision | Recall | F1-Score |
|------|----------|-----------|--------|----------|
| VGG16 | 92% | 91% | 93% | 92% |
| Model B | 85% | 84% | 86% | 85% |
| Model C | 78% | 79% | 77% | 78% |

### Key Findings
- VGG16 achieved the highest performance.
- Low misclassification rate observed in confusion matrix.
- Better feature extraction due to deeper architecture.

---

## 📈 Visualizations

### Confusion Matrix
Used to evaluate classification performance across emotions.

### UMAP Visualization
Provides manifold representation of learned facial embeddings.

### t-SNE Visualization
Helps understand clustering of emotional representations.

---

## 📁 Project Structure

```bash
Facial_Expression_Recognition_iiitk/
│
├── README.md
├── main.py
├── test.py
├── human_corr.ipynb
├── final.xlsx
├── Memory/
├── Psychology/
├── requirements.txt
└── .gitignore
