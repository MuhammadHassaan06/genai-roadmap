# 🚀 Day 4: Image Processing & Dark Mode Conversion with NumPy

Welcome to **Day 4**! Today bridges pure numerical operations with computer vision fundamentals by representing digital images as 2D/3D matrices and applying matrix manipulation to perform transformations such as color inversion (Dark Mode).

---

## 📌 Table of Contents

1. [Understanding Images as Matrices](#1-understanding-images-as-matrices)
2. [Loading & Inspecting Image Data](#2-loading--inspecting-image-data)
3. [Dark Mode Conversion (Inversion)](#3-dark-mode-conversion-inversion)
4. [Saving and Visualizing Results](#4-saving-and-visualizing-results)

---

## 1. Understanding Images as Matrices

Digital images are fundamentally stored as NumPy arrays (`ndarrays`):
* **Grayscale Images:** Represented as 2D matrices where each entry is a pixel value ranging from `0` (Black) to `255` (White).
* **Color Images (RGB):** Represented as 3D matrices with dimensions `(height, width, channels)` for Red, Green, and Blue channels.

---

## 2. Loading & Inspecting Image Data

Convert image files into NumPy arrays using libraries like `PIL` (Pillow) or `Matplotlib`:

```python
import numpy as np
from PIL import Image


img = Image.open('sample.png')
img_matrix = np.array(img)

print("Image Matrix Shape:", img_matrix.shape)
print("Data Type:", img_matrix.dtype)