# Bigram Transformer Language Model (GPT-from-scratch)

A hands-on, from-scratch implementation of a character-level Transformer-based language model using only PyTorch. This project demonstrates the core concepts of self-attention and sequence modeling by training a bigram-based GPT on the Tiny Shakespeare dataset. Walk through the complete workflow—from data loading and model definition to training loop, evaluation metrics, and text sampling—to see how transformer architectures generate coherent text at the character level.

## Features

* **BigramLanguageModel**: Single-layer Transformer with self-attention
* **Dataset**: Trained on the Tiny Shakespeare dataset (automatically downloaded)
* **End-to-end**: Includes training loop, evaluation, and text generation
* **Lightweight**: Minimal dependencies and \~200 lines of code

## Requirements

* Python 3.7+
* PyTorch

## Installation

```bash
# Clone the repository
git clone https://github.com/tahangz/Character-level-GPT
cd Character-level-GPT

# Install dependencies
pip install torch
```

## Usage

1. **Open the notebook**:

   ```bash
   jupyter notebook MiniGPT_Char.ipynb
   ```
2. **Run all cells** to train the model and sample text.

*Training parameters (can be modified in the notebook):*

* `batch_size`
* `block_size` (context length)
* `n_embd` (embedding size)
* `learning_rate`
* `max_iters`

## Project Structure

```
MiniGPT_Char.ipynb   # Jupyter notebook with full implementation
```

## References

* [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
* [nanoGPT by Andrej Karpathy](https://github.com/karpathy/nanoGPT)
