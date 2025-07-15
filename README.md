# Vision Models & VQA Experiments

This repository contains experiments on **Visual Question Answering (VQA)** using **ResNet** and **Vision Transformer (ViT)** architectures to handle image input, and CNNs, RNNs, LSTMs, attention-based LSTMs models to handle text input.
---


## Main Features

- **Dataset Analysis**:
  - Generate statistics and plots for class distribution, image sizes, and more.

- **Vision Model Fine-Tuning**:
  - **ResNet**: Training and validation with accuracy and loss metrics.
  - **ViT**: Transformer-based fine-tuning optimized for custom datasets.

- **Visual Question Answering (VQA)**:
  - Implement VQA pipelines combining:
    - **Feature Extractors**: CNN-based (ResNet) or Transformer-based (ViT).
    - **Language Model** for question understanding and answer generation (CNNs, RNNs, LSTMs, attention-based LSTMs)
