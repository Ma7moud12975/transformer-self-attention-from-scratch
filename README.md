# Transformer Self-Attention from Scratch

<img width="1000" height="667" alt="image" src="https://github.com/user-attachments/assets/847783c1-21de-4fd2-b839-12fddf96307e" />


This repository provides a clean and minimal implementation of the **self-attention mechanism** used in Transformer models, built from scratch using PyTorch.

It is designed for educational purposes to help understand how attention works mathematically and computationally.

---

## 🚀 Features

- Implementation of Scaled Dot-Product Attention
- Step-by-step computation of Q, K, V matrices
- Attention score calculation and softmax normalization
- Visualization of attention weights
- Simple and readable PyTorch code

---

## What is Self-Attention?

Self-attention allows each word in a sentence to focus on other relevant words when forming its representation.

Mathematically:


Attention(Q, K, V) = softmax(QKᵀ / √dₖ) V


---

##  Example

Input sentence:

"What are the symptoms of diabetes?"


Output:
- Attention weights matrix showing how each word attends to others
- Context-aware embeddings


