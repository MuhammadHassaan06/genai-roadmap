# 🚀 Day 2: Advanced NumPy Operations & Data Manipulation

Welcome to **Day 2** of learning NumPy! Today covers essential array manipulation concepts, including indexing, sorting, filtering, restructuring arrays, and working through practical challenges and projects.

---

## 📌 Table of Contents

1. [NumPy Array Operations](#1-numpy-array-operations)
2. [Indexing & Slicing](#2-indexing--slicing)
3. [Sorting](#3-sorting)
4. [Filtering & Searching](#4-filtering--searching)
   - [Fancy Indexing vs np.where](#fancy-indexing-vs-npwhere)
5. [Adding and Removing Data](#5-adding-and-removing-data)
6. [Array Compatibility & Concatenation](#6-array-compatibility--concatenation)
7. [Splitting Arrays](#7-splitting-arrays)
8. [Challenge (Matrix Manipulation)](#8-challenge-matrix-manipulation)
9. [Mini Project: Student Result Analysis](#9-mini-project-student-result-analysis)

---

## 1. NumPy Array Operations
Learn how vectorized operations allow fast mathematical computations on arrays without using slow Python `for` loops.

---

## 2. Indexing & Slicing
Accessing specific elements, entire rows, columns, or diagonal elements from 1D and 2D arrays using step slicing (e.g., `::-1`).

---

## 3. Sorting
Using `np.sort()` to sort arrays along different axes (rows/columns) in ascending or descending order.

---

## 4. Filtering & Searching
Filtering elements based on conditions (Boolean Masking).

### Fancy Indexing vs np.where
* **Fancy Indexing / Boolean Masking:** Extract elements directly using conditions (e.g., `arr[arr > 5]`).
* **`np.where()`:** Returns the indices where conditions are met, or allows replacing elements (e.g., `np.where(condition, if_true, if_false)`).

---

## 5. Adding and Removing Data
Dynamic modifications of arrays:
* `np.append()` – Add values at the end.
* `np.insert()` – Insert values at specific indices.
* `np.delete()` – Remove elements along an axis.

---

## 6. Array Compatibility & Concatenation
Combining multiple arrays together using `np.vstack()`, `np.hstack()`, and `np.concatenate()`.

---

## 7. Splitting Arrays
Dividing a single array into multiple sub-arrays using `np.split()`, `np.vsplit()`, or `np.hsplit()`.

---

## 8. Challenge (Matrix Manipulation)
**Task:** Create a 3x3 matrix and perform loop-free extraction:
* Extract first & last rows.
* Extract first & last columns.
* Extract main diagonal elements using `np.diagonal()`.
* Reverse elements in every row using `matrix[:, ::-1]`.

---

## 9. Mini Project: Student Result Analysis
**Task:** Analyze test scores of 10 students using NumPy statistical functions.
* Calculate **Total**, **Average**, **Max**, **Min**, **Standard Deviation**, and **Median**.
* Extract scores of students performing above average using **Boolean Indexing**.

---

## 🛠️ Requirements & Installation

Make sure you have NumPy installed:

```bash
pip install numpy