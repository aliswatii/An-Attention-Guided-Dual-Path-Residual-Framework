#  Alzheimer’s Disease Detection & Classification  
**An Attention-Guided Dual-Path Residual Framework**  
Jupyter Notebook Implementation
https://github.com/aliswatii/An-Attention-Guided-Dual-Path-Residual-Framework. It’s tailored to highlight how anyone can run the Jupyter Notebook on a GPU for Alzheimer’s Disease detection and classification:

##  Overview

This repository implements an **Attention-Guided Dual-Path Residual Framework** for MRI-based Alzheimer’s Disease (AD) detection and classification. The code is provided as a **Jupyter Notebook (`.ipynb`)**, designed to run seamlessly on any GPU-equipped environment—such as local GPUs, Google Colab, Kaggle, or other cloud platforms.

---

##  Repository Contents

- `AttentionGuidedDualStreamFrameworkFiveFoldCrossValidation.ipynb`  
  The main notebook that includes:
  - Data loading and preprocessing (e.g., normalization, resizing)
  - Dual-path architectural implementation with residual blocks and attention
  - Training protocols (e.g., five-fold cross-validation)
  - Evaluation metrics and result visualizations

---

##  Key Features

| Feature | Description |
|--------|-------------|
| **GPU-Ready** | Automatically utilizes any available GPU to accelerate training and inference. |
| **Dual-Path Residual Architecture** | Processes spatial and semantic features in parallel to improve detection of subtle AD-related changes. |
| **Attention Mechanism** | Dynamically focuses on clinically relevant brain regions to enhance interpretability and accuracy. |
| **Cross-Validation** | Supports robust evaluation with five-fold cross-validation to help evaluate model generalization. |

---

##  Prerequisites

Ensure you have the following software installed (can be installed via pip or conda):
Dataset ADNI and PPMI

- Python (recommended ≥ 3.8)  
- TensorFlow  
- Keras (if not included in TensorFlow version)  
- NumPy  
- Pandas  
- Matplotlib  
- scikit-learn  
- Jupyter Notebook

---

##  Running Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/aliswatii/An-Attention-Guided-Dual-Path-Residual-Framework.git
   cd An-Attention-Guided-Dual-Path-Residual-Framework
