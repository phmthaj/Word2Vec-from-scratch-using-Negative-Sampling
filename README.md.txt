# Word2Vec from Scratch using Negative Sampling (PyTorch)

Implementation of **Word2Vec Skip-gram with Negative Sampling (SGNS)** from scratch in PyTorch.  
This project trains word embeddings on a given corpus and allows querying for similar words.

---

## ✨ Features
- Pure **PyTorch** implementation (no gensim, no external word2vec libraries).
- **Skip-gram architecture** with **Negative Sampling**.
- Customizable:
  - Vocabulary size, embedding dimension.
  - Window size, number of negative samples.
- Training loop with `DataLoader`.
- Export embeddings to `.vec` format (compatible with gensim / fastText).
- Simple utilities to query most similar words using cosine similarity.

---