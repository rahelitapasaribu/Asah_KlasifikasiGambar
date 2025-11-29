# 🍎 Fruits-360 Image Classification (CNN)

A Convolutional Neural Network (CNN) built using **TensorFlow** to classify images from the **Fruits-360** dataset.  
The model recognizes **227 fruit and vegetable classes** with over **95% accuracy**.

---

## 🧠 Model Summary
- Input: 100×100 RGB images  
- Layers: Conv2D, MaxPooling2D, BatchNormalization, Dropout  
- Optimizer: Adam (lr=1e-4)  
- Loss: Categorical Crossentropy  
- Epochs: 30 (with early stopping & custom callback)  

---

## 📊 Dataset
- **Source:** [Kaggle - Fruits 360](https://www.kaggle.com/moltean/fruits)  
- **Total:** ±159,000 images  
- **Classes:** 227  
- **Split:** 80% Train • 10% Validation • 10% Test  

Data augmentation used: rotation, zoom, shift, flip, and rescaling.

---

## 📦 Exported Formats
- SavedModel (`saved_model/`)
- TensorFlow Lite (`model.tflite`)
- TensorFlow.js (`tfjs_model/`)

---

## 👩‍💻
**Rahelita Pasaribu, Udayana University**
