# 🔥 GPT-2 From Scratch Using TensorFlow & Keras

This project implements a **GPT-2 style transformer model from scratch** using **TensorFlow** and **Keras**, with multi-head self-attention, feed-forward layers, and causal masking.

---

## 🧠 Architecture

- **Token + Positional Embeddings**
- **Multi-Head Self Attention**
- **Feed-Forward Network (FFN)**
- **Residual + Layer Normalization**
- **Causal Masking**
- Final Dense layer for vocabulary prediction

Inspired by OpenAI’s GPT-2 model architecture.

---

## 🚀 Features

- Clean, minimal code (easy to learn)
- Fully modular: Embedding, TransformerBlock, Attention, FFN
- TensorFlow & Keras native
- Ideal for:
  - ML learners
  - Architecture understanding
  - Lightweight GPT experiments

---

## 🛠️ Model Hyperparameters

```python
vocab_size = 50257
max_length = 1024
d_model = 768
num_heads = 12
dff = 3072
num_layers = 12
