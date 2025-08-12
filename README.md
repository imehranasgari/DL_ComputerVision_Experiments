# CIFAR-10 Deep Learning Experiments

## Problem Statement and Goal of Project
Train, evaluate, and experiment with convolutional neural network architectures on the CIFAR-10 dataset to explore the effects of different training techniques, optimizations, and regularization methods.

## Solution Approach
- Implemented and trained a CNN model using TensorFlow/Keras for image classification.
- Applied data augmentation (random flips, translations, zoom) to improve generalization.
- Utilized mixed precision training for faster computation on GPUs.
- Experimented with Batch Normalization and activation function changes.
- Compared SELU activation vs Batch Normalization impact on training.
- Tested Dropout regularization and Monte-Carlo Dropout for uncertainty estimation.
- Applied L1/L2 regularization for controlling model complexity.
- Compared different optimizers for training performance.

## Technologies & Libraries
keras, math, matplotlib, numpy, os, tensorflow

## Description about Dataset
CIFAR-10 dataset (60,000 32x32 color images in 10 classes, with 50,000 training and 10,000 test images).

## Installation & Execution Guide
1. Clone the repository.
2. Install dependencies:  
   ```bash
   pip install tensorflow keras numpy matplotlib
   ```
3. Run the desired notebook in Jupyter or JupyterLab.

## Key Results / Performance
Not provided.

## Screenshots / Sample Output
Not provided.

## Additional Learnings / Reflections
- This repository contains both accuracy-focused and exploratory notebooks to illustrate understanding of deep learning concepts.
- Some notebooks intentionally prioritize learning and experimentation over achieving state-of-the-art performance metrics.

## 👤 Author

**Mehran Asgari**  
**Email:** [imehranasgari@gmail.com](mailto:imehranasgari@gmail.com)  
**GitHub:** [https://github.com/imehranasgari](https://github.com/imehranasgari)

---

## 📄 License
This project is licensed under the MIT License – see the `LICENSE` file for details.

> 💡 *Some interactive outputs (e.g., plots, widgets) may not display correctly on GitHub. If so, please view this notebook via [nbviewer.org](https://nbviewer.org) for full rendering.*
