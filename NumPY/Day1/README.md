# 🚀 Day 1: NumPy Array & Fundamentals

Welcome to **Day 1** of the NumPy learning roadmap! Today covers the foundational concepts of NumPy, understanding arrays, multidimensional structures, properties, reshaping, and basic indexing.

---

## 📌 Table of Contents

1. [Creating Array](#1-creating-array)
2. [List vs NumPy Array](#2-list-vs-numpy-array)
3. [Creating Array from Scratch](#3-creating-array-from-scratch)
4. [Vector, Matrix, Tensor](#4-vector-matrix-tensor)
5. [Array Properties](#5-array-properties)
6. [Array Reshaping](#6-array-reshaping)
7. [Converting 1D Array into 2D Array](#7-converting-1d-array-into-2d-array)
8. [Indexing and Slicing](#8-indexing-and-slicing)
9. [Practice & Practice Questions](#9-practice--practice-questions)

---

## 1. Creating Array
Introduction to NumPy arrays using `np.array()` by converting standard Python lists and tuples into NumPy ndarrays.

---

## 2. List vs NumPy Array
Comparing Python lists with NumPy arrays:
* **Performance:** NumPy arrays are significantly faster due to contiguous memory allocation and C implementation.
* **Memory Efficiency:** Uses less memory compared to Python lists.
* **Vectorization:** Allows element-wise operations without explicit loops.

---

## 3. Creating Array from Scratch
Generating arrays using built-in NumPy functions:
* `np.zeros()` – Creates an array filled with zeros.
* `np.ones()` – Creates an array filled with ones.
* `np.arange()` – Creates sequences of numbers with a specified step size.
* `np.linspace()` – Generates evenly spaced numbers over a specified interval.
* `np.random.rand()` / `np.random.randint()` – Generates arrays with random values.

---

## 4. Vector, Matrix, Tensor
Understanding array dimensions ($N$-dimensional arrays):
* **Vector (1D):** Single row or column of elements.
* **Matrix (2D):** Table of elements with rows and columns.
* **Tensor (3D+):** Multi-dimensional arrays used in deep learning and advanced data science.

---

## 5. Array Properties
Inspecting array characteristics:
* `arr.ndim` – Number of dimensions.
* `arr.shape` – Tuple representing array dimensions (rows, columns).
* `arr.size` – Total number of elements.
* `arr.dtype` – Data type of the array elements.

---

## 6. Array Reshaping
Changing the layout and structure of an array using `.reshape()` without modifying its original data.

---

## 7. Converting 1D Array into 2D Array
Transforming 1D flat vectors into 2D matrices using `.reshape(rows, cols)` or `np.newaxis`.

---

## 8. Indexing and Slicing
Accessing and modifying specific elements or sub-sections of 1D and 2D arrays:
* **Basic Indexing:** `arr[0]` or `arr[1, 2]`
* **Basic Slicing:** `arr[start:stop:step]`

---

## 9. Practice & Practice Questions
Hands-on exercises and practice problems to reinforce concepts learned throughout Day 1.

---

## 🛠️ Requirements & Setup

Make sure you have NumPy installed:

```bash
pip install numpy