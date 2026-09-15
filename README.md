# GPT model from scratch using PyTorch

GPT model implemented from scratch using PyTorch, following the **GPT-2 124M architecture**.

**Pipeline:**

```text
text → tokens → embeddings → transformer → probabilities → next token → text
```

### architecture

* **vocabulary size:** 50,257 tokens
* **context length:** 1,024 tokens
* **embedding dimension:** 768
* **attention heads:** 12
* **transformer blocks:** 12
* **feed-forward dimension:** 3,072
* **dropout:** 0.1

### components

* token & positional embeddings
* multi-head self-attention
* causal masking
* layer normalization
* GELU activation
* feed-forward networks
* residual connections
* autoregressive text generation

> **note:** The model is not trained and does not use pretrained weights, so the generated text will be meaningless. The project is intended to demonstrate the GPT architecture and text-generation process.
