# SSELF: Self-Supervised Ensemble Learning Framework for PolSAR Image Classification

This repository contains the implementation of **SSELF**, a novel Self-Supervised Ensemble Learning Framework for polarimetric synthetic aperture radar (PolSAR) image classification using limited labeled training samples.

## 🔍 Overview

PolSAR image classification with few labeled samples is a challenging task. SSELF addresses this by combining:

- **EfficientNet-B0** as the backbone for deep spatial-polarimetric feature extraction.
- **Self-supervised learning** using a correlation-based objective for robust feature representation.
- **Deep Curriculum Learning (DCL)** to train the network progressively based on patch difficulty estimated via entropy-alpha decomposition.
- **Ensemble Learning (EL)** at feature and view levels to improve classification performance using multi-scale spatial features and multiple polarimetric bands.

## 🚀 Key Features

- Works with **few labeled samples**.
- Extracts discriminative features in a **self-supervised** way.
- Leverages **curriculum learning** to enhance model robustness.
- Improves results using a **two-level ensemble strategy**.

## 📁 Structure

- `models/`: Network architectures (EfficientNet, DCL, etc.)
- `datasets/`: Preprocessing scripts for PolSAR data
- `training/`: Curriculum learning and self-supervised training logic
- `inference/`: Scripts for evaluation and visualization

## 🧠 Citation

If you use this work, please cite our paper.
Darvishnezhad, Mohsen, and Mohammad Ali Sebt. "A novel self‐supervised ensemble learning framework for land use and land cover classification of polarimetric synthetic aperture radar images." IET Radar, Sonar & Navigation 18, no. 3 (2024): 379-409.

