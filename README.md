# GhostNet_CBAM
Enhancing Lightweight CNNs: Modifications to GhostNet for Improved Efficiency and Stability


This repository contains the implementation of a modified GhostNet architecture, enhanced with **CBAM** (Convolutional Block Attention Module) and **ASPP** (Atrous Spatial Pyramid Pooling) to improve feature extraction, generalization, and stability on lightweight image classification tasks.

📘 **Project Title**: Enhancing Lightweight CNNs: Modifications to GhostNet for Improved Efficiency and Stability  

---

## 🚀 Key Contributions

- 🔧 **GhostNet Modifications**: Added CBAM for attention and ASPP for multi-scale feature extraction.
- 📉 **Parameter Reduction**: From 3.91M to 3.59M parameters.
- 📈 **Improved Generalization**: Reduced overfitting and improved test accuracy consistency.
- 📊 **Tested On**: STL-10 and CIFAR-10 benchmark datasets.

---

## 🧠 Model Architecture

- ✅ **Original**: GhostNet with Ghost modules for efficient convolution.
- 🧩 **Modified**:
  - **CBAM**: Enhances spatial and channel-wise attention.
  - **ASPP**: Extracts multi-scale contextual features (used for STL-10 only).

---