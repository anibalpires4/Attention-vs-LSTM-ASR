# Attention vs LSTM in Sequence-to-Sequence ASR

This project compares two encoder-decoder architectures for Automatic Speech Recognition (ASR):
1. **LSTM-Based Decoder**: Sequential processing with hidden states for temporal dependencies.
2. **Attention-Based Decoder**: Parallel processing with dynamic attention for global context.

## Overview
- **Dataset**: LJ Speech Dataset (v1.1)
- **Metrics**: Jaccard Similarity, Cosine Similarity, Damerau-Levenshtein Similarity
- **Objective**: Evaluate performance and scalability for ASR tasks.

## Key Results
| Metric                         | **LSTM Decoder** | **Attention Decoder** |
|--------------------------------|------------------|-----------------------|
| **Final Test Loss**            | 1.1828          | 1.1604               |
| **Jaccard Similarity**         | 0.7149          | 0.7645               |
| **Cosine Similarity**          | 0.8324          | 0.8652               |
| **Damerau-Levenshtein Similarity** | 0.5087          | 0.6333               |

- **LSTM**: Struggles with long-range dependencies due to sequential processing.
- **Attention**: Excels in scalability and global dependency modelling.

## Methodology
- **LSTM Decoder**: Sequential token processing, hidden state updates, and cross-attention layers.
- **Attention Decoder**: Parallel token processing, position embeddings, and attention layers.

## Technologies
- **Language**: Python
- **Framework**: PyTorch
- **Tools**: Jupyter Notebook, NLP Evaluation Metrics

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/anibalpires4/Attention-vs-LSTM-ASR.git
