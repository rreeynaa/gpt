# GPT model from scratch using PyTorch

GPT model implemented from scratch using PyTorch, following the **GPT-2 124M architecture**.

**Pipeline:**

```text
Text → Tokens → Embeddings → Transformer → Probabilities → Next Token → Text
```

### Architecture

* **Vocabulary Size:** 50,257 tokens
* **Context Length:** 1,024 tokens
* **Embedding Dimension:** 768
* **Attention Heads:** 12
* **Transformer Blocks:** 12
* **Feed-Forward Dimension:** 3,072
* **Dropout:** 0.1

### Components

* Token & Positional Embeddings
* Multi-Head Self-Attention
* Causal Masking
* Layer Normalization
* GELU Activation
* Feed-Forward Networks
* Residual Connections
* Autoregressive Text Generation

> **Note:** The model is not trained and does not use pretrained weights, so the generated text will be meaningless. The project is intended to demonstrate the GPT architecture and text-generation process.
