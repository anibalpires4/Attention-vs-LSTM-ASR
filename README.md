# Attention vs LSTM in Sequence-to-Sequence ASR

This project compares two encoder-decoder architectures for Automatic Speech Recognition (ASR) tasks:
1. **LSTM-Based Model**: A traditional recurrent architecture for sequence learning.
2. **Attention-Based Model**: A modern approach that improves handling of long-range dependencies.

The analysis focuses on their performance using similarity metrics on the LJ Speech dataset.

---

## Overview
The study evaluates:
- The effectiveness of Attention vs LSTM for sequence-to-sequence ASR tasks.
- Performance metrics including:
  - **Cosine Similarity**: Measures similarity of predicted sequences.
  - **Jaccard Similarity**: Evaluates overlap between predicted and ground truth sequences.
  - **Damerau-Levenshtein Distance**: Captures sequence-level differences.
- Practical trade-offs in scalability and accuracy for real-world applications.

---

## Key Results
- **Attention-Based Model**:
  - Cosine Similarity: **86.52%**
  - Jaccard Similarity: **76.45%**
  - Damerau-Levenshtein Similarity: **63.33%**
- **LSTM-Based Model**:
  - Lower performance across all metrics, highlighting the superiority of Attention for ASR tasks.

---

## Technologies
- **Programming Language**: Python
- **Frameworks**: PyTorch
- **Tools**: Jupyter Notebook, NLP Evaluation Metrics

---

## Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/attention-vs-lstm-asr.git

