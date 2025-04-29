
# CIFAR-10 Image Classification using Neural Networks

This project demonstrates how to build and train an artificial neural network (ANN) using TensorFlow and Keras to classify images from the CIFAR-10 dataset.

---

## 📦 Dataset Overview

The CIFAR-10 dataset consists of:

- **50,000 training images** and **10,000 test images**
- Each image is **32x32 pixels** with **3 RGB channels**
- 10 classes: `airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, `truck`

### 🔍 Sample Image Data

Each image is a 3D array (32, 32, 3) where each element is a pixel's RGB value ranging from 0 to 255.

Example:
```python
X_train[0]
# Output shape: (32, 32, 3)
# Each pixel: [Red, Green, Blue]
