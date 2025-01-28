# Transformer-based Language Model from Scratch
This project implements a Transformer-based Language Model from scratch using PyTorch. The model is trained on the TinyShakespeare dataset and is capable of generating text in the style of Shakespeare. 

# Features

**Transformer Architecture**: Implements multi-head self-attention, feed-forward layers, and layer normalization.
**Character-Level Modeling**: The model operates at the character level, making it simple and interpretable.
**Training Loop**: Includes a training loop with AdamW optimizer, evaluation on validation data, and text generation.
**Checkpointing**: Saves the model architecture, weights, and tokenizer for later use.

# Requirements

Python 3.7+
PyTorch 1.10+
CUDA (optional, for GPU acceleration)
