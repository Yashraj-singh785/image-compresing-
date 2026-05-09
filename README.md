

# README.md

```md
# Image Compression Using Singular Value Decomposition (SVD)

A visual and mathematical exploration of how linear algebra can compress images using Singular Value Decomposition.

This project demonstrates how an image can be reconstructed using only the most important singular values while preserving most visual information.

---

## Project Overview

An image is fundamentally a matrix of pixel values.

Using Singular Value Decomposition (SVD), we can decompose that matrix into:

A = UΣVᵀ

Where:
- U → captures visual patterns
- Σ → stores importance of those patterns
- Vᵀ → reconstruction directions

Instead of storing the full image, we keep only the top-k singular values.

This creates:
- compression
- dimensionality reduction
- efficient representation

while still preserving most of the visual structure.

---

## What This Project Demonstrates

- Converting an image into matrix representation
- Applying Singular Value Decomposition using NumPy
- Reconstructing compressed images using top-k singular values
- Visualizing singular value decay
- Understanding low-rank approximation
- Connecting SVD to machine learning concepts

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- Jupyter Notebook

---

## Results

The image was reconstructed using different values of k:

- k = 5
- k = 20
- k = 50
- k = 100

Observation:
Even after removing a large amount of information, the image still remained recognizable.

This happens because most important visual information is concentrated in only a few singular values.

---

## Mathematical Insight

SVD decomposes a matrix into ordered components ranked by importance.

The singular values decay rapidly, meaning:
- a few components contain most information
- remaining components contribute less detail

This is the foundation of:
- image compression
- PCA
- recommender systems
- embeddings
- latent representation learning

---

## Machine Learning Connection

The same linear algebra concepts used here appear in:

- Principal Component Analysis (PCA)
- Matrix Factorization
- Recommendation Systems
- Neural Networks
- Embedding Spaces
- Dimensionality Reduction

This project helped bridge mathematical theory with practical ML intuition.

---

## Future Work

Next project in the series:

Building PCA from scratch using NumPy.

---

## Author

Yashraj Singh
```
