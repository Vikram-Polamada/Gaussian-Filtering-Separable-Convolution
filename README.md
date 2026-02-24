# 🖼️ Gaussian Filtering & Separable Convolution Demonstration (OpenCV)

A computer vision project demonstrating **Gaussian blurring**, **1D separable convolution**, and a **mathematical verification** proving that a 2D Gaussian filter is equivalent to two 1D Gaussian filters applied sequentially.

This implementation is based on the code inside **CV-TASK.ipynb** and uses **OpenCV**, **NumPy**, and **Matplotlib**.

---

## 🚀 Project Overview

This project:

- 📥 Loads an input image using OpenCV  
- 🔍 Applies **standard 2D Gaussian blur**  
- ➗ Applies **1D Gaussian blur twice** (horizontal + vertical)  
- 📊 Compares both outputs  
- 📐 Computes mathematical **difference map + difference sum**  
- ✔️ Verifies separability of Gaussian kernel  

The goal is to visually and numerically confirm that:

> **Gaussian 2D convolution = Gaussian 1D (X) + Gaussian 1D (Y)**

---

## 🧪 What the Script Does

The notebook/script performs:

1. **Image Loading**
2. **Convert BGR → RGB** (for Matplotlib)
3. **Apply 2D Gaussian Blur**
4. **Create 1D Gaussian Kernel manually**
5. **Apply Horizontal 1D Convolution**
6. **Apply Vertical 1D Convolution**
7. **Compare Results**
8. **Generate Plots**:
   - Original Image  
   - Standard 2D Gaussian Blur  
   - Separable 1D Gaussian Blur Output  
   - Hot-colored difference map  

9. **Mathematical Verification**

---

## 📝 Conclusion

This task successfully demonstrates:

- How Gaussian blur works  
- How separable convolution drastically reduces computation  
- Why Gaussian is preferred in real-time CV systems  
- A visual + numerical proof that **2D Gaussian = 1D X + 1D Y**  

It offers a foundational understanding for further CV topics like:

- Edge detection (Canny)  
- Image pyramids  
- SIFT / SURF feature extraction  

---
