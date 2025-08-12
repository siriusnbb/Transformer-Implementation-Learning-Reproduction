# Transformer Implementation (Learning Reproduction)

This repository contains my personal learning reproduction of the Transformer model,
inspired by the example code from the [Dive into Deep Learning (D2L)](https://github.com/d2l-ai/d2l-en) book.
The goal of this project is to simplify the original implementation for beginners
and provide a clearer context for each component.

## 📌 Key Features
- **Rewritten Transformer Core**: Encoder and decoder modules are implemented from scratch
  based on my understanding, with references to the structure described in D2L and other
  public resources.
- **Simplified Code Structure**: The original D2L example involves multiple nested
  functions across files; here the logic is reorganized for easier navigation and learning.
- **Beginner-Friendly**: Designed for those who want to study the Transformer architecture
  without being overwhelmed by complex function dependencies.

## 🚀 Contents
- `data/` — Data downloading and preparation scripts (adapted from D2L example code)
- `transformer.py` — Rewritten Transformer encoder and decoder implementation
- `train.py` — Training loop (adapted from D2L example code)
- `test.py` — Testing and evaluation scripts (adapted from D2L example code)

## 📚 References
- Vaswani et al., *Attention Is All You Need*, NeurIPS 2017.
- [Dive into Deep Learning (D2L)](https://github.com/d2l-ai/d2l-en)

## 📝 License
This project is released under the MIT License.

**Third-Party Notices**  
Parts of the data downloading/preparation scripts and training/evaluation code are
adapted from the Dive into Deep Learning (D2L) project, licensed under a modified MIT License.
Original copyright:

