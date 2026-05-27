# EMNIST Handwritten Letter Classification using HOG and SVM

## Project Description

This project implements handwritten character classification using the EMNIST Letters dataset with HOG (Histogram of Oriented Gradients) as feature extraction and Support Vector Machine (SVM) as the classifier.

This project was created for the Machine Vision Midterm Assessment.

---

## Dataset

Dataset used:

* EMNIST Letters Dataset
* Source: Kaggle

Dataset specifications:

* 28x28 grayscale images
* 26 letter classes
* CSV format

---

## Methods Used

### 1. Dataset Preparation

* Balanced dataset
* 100 samples per class
* Total 2600 samples
* Dataset shuffling

### 2. HOG Feature Extraction

Parameters:

* orientations = 9
* pixels_per_cell = (4,4)
* cells_per_block = (2,2)

### 3. SVM Classification

Parameter tuning using Grid Search:

* kernel
* C
* gamma

### 4. Evaluation

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Output Results

The program generates:

* Sample dataset visualization
* HOG visualization
* Confusion matrix
* Classification report

---

## Libraries Used

* numpy
* pandas
* matplotlib
* seaborn
* scikit-image
* scikit-learn
* kagglehub

---

## How to Run

```bash
pip install -r requirements.txt
python main.py
```

---
