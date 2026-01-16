# 🐾 PawNet: Cat and Dog Image Classification

PawNet is a deep learning–based image classification project that accurately distinguishes between **cats and dogs** using **Convolutional Neural Networks (CNNs)**.  
The model is trained on a **large-scale dataset of 100,000 labeled images**, making it robust and reliable for real-world predictions.

This project demonstrates the complete **computer vision and deep learning pipeline**, from data preprocessing to model evaluation and inference.

---

## 📌 Project Overview

- **Problem Type:** Binary Image Classification  
- **Classes:** Cat 🐱, Dog 🐶  
- **Dataset Size:** 100,000 images  
- **Approach:** Supervised Learning  
- **Model Type:** Convolutional Neural Network (CNN)

---

## 📂 Dataset Details

- Total Images: **100,000**
- Classes:
  - Cats
  - Dogs
- Dataset Split:
  - Training Set
  - Validation Set
  - Test Set
- Images were resized and normalized before training.
- Data augmentation was applied to improve generalization.

> ⚠️ Dataset is not included in the repository due to size limitations.

---

## 🧠 Model Architecture

The model is built using a **CNN architecture**, consisting of:
- Convolutional layers for feature extraction  
- ReLU activation functions  
- MaxPooling layers for dimensionality reduction  
- Fully connected (Dense) layers  
- Sigmoid activation for binary classification  

The architecture is designed to balance **accuracy and computational efficiency**.

---

## 🛠️ Technologies & Libraries Used

### Programming Language
- **Python**

### Libraries & Frameworks
- **TensorFlow**
- **Keras**
- **NumPy**
- **Matplotlib**
- **OpenCV** (for image handling, if used)

---

## ⚙️ Workflow

1. Dataset loading and labeling  
2. Image preprocessing (resizing, normalization)  
3. Data augmentation  
4. Model building using CNN  
5. Model training on large-scale data  
6. Evaluation on test dataset  
7. Prediction on unseen images  

---

## 📊 Model Performance

- Achieves **high accuracy** due to large dataset size
- Reduced overfitting using:
  - Data augmentation
  - Validation-based training
- Performance evaluated using accuracy and loss metrics

*(Exact accuracy may vary based on system and training parameters)*

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/PawNet.git](https://github.com/mayanksinghgitu/Binary-Image-Classifier-Cat-and-Dog-using-CNN.git)
