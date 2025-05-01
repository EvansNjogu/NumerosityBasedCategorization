[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![Pytorch](https://img.shields.io/badge/PyTorch-2.0.1-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
# Numerosity-Based Categorization in Neural Networks

This repository contains the complete source code, datasets, and experiments accompanying my MSc thesis: **"Numerosity-Based Categorization in Neural Networks."**  
The project investigates how deep learning models can perceive and categorize quantities into abstract concepts such as **"few"**, **"medium"**, and **"many"**, instead of relying on precise counts.

> 📚 This work has been officially submitted and is pending approval and defense as part of the MSc program at Eötvös Loránd University (ELTE), Faculty of Informatics (2025).

## Overview

Precise counting is often unnecessary or impractical in real-world scenarios. This research explores how neural networks can learn **approximate quantity categories**, enabling faster, more flexible reasoning.  
The project evaluates both baseline convolutional (CNN) models and CNN + Transformer hybrid models across a range of synthetic and structured datasets, including:

- Dot patterns
- Silhouette compositions (MPEG-7 inspired)
- Controlled pixel-ratio datasets

Key research questions include:
- Can neural models abstract numerosity beyond low-level visual cues?
- How do models generalize across variations such as occlusion, clustering and shape changes?
- Do models exhibit human-like biases (e.g., underestimation in dense scenes)?

## Highlights

- Developed custom datasets to test generalization under controlled variations (dot, silhouette, pixel-ratio).  
- Designed and trained CNN and CNN + Transformer models for numerosity categorization.  
- Demonstrated cognitive parallels between human and neural model perception (e.g., context-dependent numerosity biases).  
- Evaluated cross-domain transfer learning performance.  
- Thesis successfully submitted and awaiting defense.

## Usage

The repository includes:
- Dataset generation scripts
- Model implementations (PyTorch)
- Experiment runners
- Evaluation and visualization tools (confusion matrices, sample predictions)


## Objectives

- Generalization: Train neural networks to learn abstract numerosity concepts that are independent of specific data formats or modalities.

- Scalability: Build models capable of handling diverse datasets and adapting to the complexities of real-world applications.

- Efficiency: Develop approximate quantification methods that are computationally efficient yet maintain high accuracy.

## Contact

For any questions or collaboration opportunities, feel free to reach out at [hey@njoguevans.me](mailto:hey@njoguevans.me).
