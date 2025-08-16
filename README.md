# MNIST Digit Classification with TensorFlow & Keras

This project demonstrates how to build and train a simple **Neural Network** to classify handwritten digits from the **MNIST dataset** using **TensorFlow (Keras API)**.  
The notebook explores different architectures and techniques, from a single dense layer to deeper models with hidden layers and flattening layers.

---

## 📌 Features
- Load and preprocess the **MNIST dataset** (handwritten digits 0–9).
- Visualize sample training images using `matplotlib`.
- Normalize pixel values for better training performance.
- Train models with different architectures:
  - **Single Dense Layer Model** (baseline).
  - **Dense Model with Hidden Layer** (using ReLU activation).
  - **Flatten + Dense Layers** (avoiding manual reshaping).
- Evaluate model accuracy and loss on **test data**.
- Generate predictions and compare with ground truth.
- Create and visualize a **Confusion Matrix** with **Seaborn**.

---

## 📊 Dataset
- **Training set**: 60,000 images (28×28 pixels).  
- **Test set**: 10,000 images.  
- Each image is grayscale, representing digits **0–9**.  
- Dataset is automatically downloaded via `keras.datasets.mnist`.

---

## ⚙️ Installation & Requirements
This notebook is designed for **Google Colab**, but it can also run locally.

### Dependencies
```bash
pip install tensorflow matplotlib seaborn numpy
