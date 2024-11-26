# Attention vs LSTM in Sequence-to-Sequence ASR

This repository focuses on the implementation and analysis of encoder-decoder architectures for Automatic Speech Recognition (ASR). The project compares:
1. **LSTM-Based Encoder-Decoder**: A traditional recurrent approach to sequence learning.
2. **Attention-Based Encoder-Decoder**: A modern approach that excels in handling long-range dependencies.

---

## Overview
This project evaluates the performance of these architectures on the LJ Speech dataset. The comparison highlights:
- **Model Performance**: Metrics include Cosine Similarity, Jaccard Similarity, and Damerau-Levenshtein Distance.
- **Scalability**: Attention mechanisms demonstrate improved scalability for longer sequences.
- **Trade-offs**: LSTM struggles with long-range dependencies, while Attention mechanisms offer significant improvements in sequence modelling.

---

## Key Results
- **Attention-Based Model**:
  - Cosine Similarity: **86.52%**
  - Jaccard Similarity: **76.45%**
  - Damerau-Levenshtein Similarity: **63.33%**
- **LSTM-Based Model**:
  - Lower performance across all metrics, demonstrating the limitations of traditional recurrent architectures.

---

## Technologies
- **Programming Language**: Python
- **Frameworks**: PyTorch
- **Tools**: Jupyter Notebook, NLP Evaluation Metrics

---

## Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/anibalpires4/Attention-vs-LSTM-ASR.git

