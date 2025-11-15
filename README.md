# MNIST 5-Detector

## Overview
This project detects the digit **5** in the MNIST dataset using binary classification.  
Two classifiers are compared: **SGDClassifier** and **RandomForestClassifier**.

---

## Dataset
- MNIST dataset: 70,000 images (28x28 pixels)  
- Training set: 60,000 images  
- Test set: 10,000 images  
- Labels: 0–9, converted to binary (5 vs not-5)

---

## Classifiers
1. **SGDClassifier**
   - Precision: 0.837  
   - Recall: 0.651  
   - F1-score: 0.733  
   - ROC AUC: 0.960

2. **RandomForestClassifier**
   - Precision: 0.990  
   - Recall: 0.873  
   - F1-score: 0.928  
   - ROC AUC: 0.998

---

## Observations
- Random Forest outperforms SGD in detecting 5s.  
- Precision/Recall tradeoff helps adjust the classifier based on desired performance.  

---

## How to Run
1. Install dependencies:
```bash
pip install numpy matplotlib scikit-learn
