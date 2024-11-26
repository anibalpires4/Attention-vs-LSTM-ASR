# Deep Learning: Architectures and Optimization

This repository contains implementations of deep learning models and techniques, developed as part of coursework at IST ULisboa. The focus is on exploring and comparing modern deep learning architectures and optimization techniques.

---

## Contents
This repository includes the implementation of:

### Optimizing Transformer Self-Attention
- **Objective**: Analyze and reduce the computational complexity of the self-attention mechanism in transformers.
- **Key Points**:
  - Self-attention scales quadratically with sequence length \(O(L^2D)\), creating challenges for longer sequences.
  - Approximations using **McLaurin series** and feature maps provide a scalable alternative, reducing the computational burden.
  - Sparse attention mechanisms and dimensionality reduction techniques offer significant performance improvements.
- **Details**: This section focuses on theoretical analysis, highlighting strategies to enhance scalability and efficiency in transformer architectures.

### Convolutional Neural Networks for Image Classification
- **Objective**: Analyze and compare CNN architectures with and without max-pooling layers.
- **Highlights**:
  - Implementations of two CNN configurations:
    1. With max-pooling layers for better generalization.
    2. Without max-pooling layers to retain spatial detail.
  - Training conducted with different learning rates, evaluated on validation/test accuracy.
  - Best test accuracy achieved: **83.7%** (with max-pooling).

### Encoder-Decoder Architectures for Automatic Speech Recognition
- **Objective**: Comparative analysis of LSTM-based and Attention-based architectures for ASR.
- **Highlights**:
  - Implementation of LSTM and Transformer-based encoder-decoder models.
  - Evaluation conducted on LJ Speech dataset using string similarity metrics (Jaccard, Cosine, Damerau-Levenshtein).
  - The Attention mechanism outperformed LSTM in all metrics, showcasing superior performance in handling long-range dependencies.

---

## Technologies
- **Programming Language**: Python
- **Frameworks**: PyTorch
- **Tools**: Jupyter Notebook, Google Colab
