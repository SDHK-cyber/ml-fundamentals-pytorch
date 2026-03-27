[README.md](https://github.com/user-attachments/files/26307785/README.md)
# ml-fundamentals-pytorch

A self-directed series of machine learning projects built from scratch in PyTorch, progressing from simple regression to classification and beyond.

Each problem is solved independently — no high-level sklearn wrappers. The goal is to deeply understand the full ML pipeline: data generation, model design, training, evaluation, and interpretation.

---

## Structure

| # | Problem | Type | Key Concepts |
|---|---------|------|--------------|
| 01 | x² | Regression | Basic pipeline, MSELoss, Adam |
| 02 | e^(-x²)sin(5x) | Regression | Oscillatory functions, overfitting |
| 03 | Sinc | Regression | Discontinuity at origin, generalization |
| 04 | sin(x)cos(y) | Regression | 2D input, surface fitting |
| 05 | 3D regression | Regression | High-dimensional input, curse of dimensionality |
| 06 | 2D Gaussian | Regression | Multi-output, Gaussian surfaces |
| 07 | Binary classification | Classification | BCEWithLogitsLoss, sigmoid, decision boundary |

---

## Stack

- Python 3.x
- PyTorch
- NumPy
- Matplotlib

---

## Setup

```bash
git clone https://github.com/YOUR_USERNAME/ml-fundamentals-pytorch.git
cd ml-fundamentals-pytorch
pip install -r requirements.txt
```

All notebooks are self-contained and run on Google Colab or locally.

---

## Goals

- Build intuition for the ML pipeline through hands-on coding
- Apply ML to physics-motivated problems
- Develop debugging and evaluation skills (loss curves, metrics, visualizations)

---

## Status

🟢 Regression — complete  
🔄 Classification — in progress  
🔲 PINNs — upcoming  
🔲 HEP applications — upcoming
