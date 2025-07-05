# Bigram Transformer Language Model (GPT-from-scratch)

A minimal character-level GPT (bigram) implemented from scratch in PyTorch. Inspired by Andrej Karpathy’s nanoGPT example and the original "Attention Is All You Need" paper.

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
git clone <your-repo-url>
cd <your-repo-folder>

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
