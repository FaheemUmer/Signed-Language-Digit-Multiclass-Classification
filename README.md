🧠 Sign Language Digit Multiclass Classification

This project implements a multiclass image classification system to recognize **hand-signed digits (0–9)** using deep learning models. The goal is to train and compare different architectures for accurately classifying sign language digit gestures.

---

## 📌 Objective

To classify hand gesture images representing digits (0–9) using CNN and other deep learning models, enabling applications in assistive technologies, education, and real-time sign recognition.

---

## 🗂️ Dataset Details

- **Source**: Custom dataset / Kaggle / MNIST-style Sign Language Digits  
- **Input Format**: RGB or grayscale images of hand signs  
- **Classes**: 10 classes (0–9)  
- **Preprocessing**:
  - Image resizing and normalization  
  - One-hot encoding of labels  
  - Train/test/validation split  

---

## 🧠 Models Implemented

- Feedforward Neural Network (FNN)  
- Convolutional Neural Network (CNN)  
- Fine-tuned pre-trained models (e.g., ResNet18 / ResNet50)  
- Model performance comparison with accuracy and confusion matrix

---

## 🛠️ Technologies Used

- Python 3.x  
- PyTorch  
- NumPy  
- Matplotlib / Seaborn  
- scikit-learn  

---


---

## 📈 Results & Evaluation

- Models are evaluated using:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1-score
- Visualization of sample predictions and misclassifications included

---

## 🔮 Future Work

- Deploy model using Flask or Streamlit for real-time recognition  
- Integrate webcam-based gesture input  
- Extend dataset to include full sign language alphabets  
- Improve accuracy with data augmentation  

---

