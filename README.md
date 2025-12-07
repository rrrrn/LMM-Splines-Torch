# PyTorch Smoothing Splines for GLMM

This repository provides a high-performance framework for fitting **Generalized Linear Mixed Models (GLMMs)** with **smoothing splines** using **PyTorch**. The implementation enables efficient modeling of non-linear covariate effects while mixed structure in real-world datasets with the capability of incorporating smoothing spline terms.

We support likelihood-based inference on spline terms, simulation infrastructure for benchmarking and comparison studies, and tools for scalable application to large biomedical cohort datasets such as the **All of Us (AoU)** Research Program.

---

## ✨ Features

- Fast spline-based GLMM fitting with GPU acceleration support
- Penalized smoothing spline construction and optimization
- Explicit modeling of random effects for batch correction
- Statistical testing of spline non-linearity
- Robust and reproducible simulation pipelines
- Example notebooks demonstrating model usage

---

## 📂 Repository Structure

| File / Folder | Description |
|--------------|-------------|
| `LMMFit.py` | Linear mixed model utilities |
| `LMMSSFit.py` | Core spline-based GLMM fitting implementation |
| `SmoothingSpline.py` | Spline basis generation + smoothing penalty functions |

---
