# Transformer Implementation (Learning Reproduction)

This repository contains my personal learning reproduction of the Transformer model,
inspired by the example code from the [Dive into Deep Learning (D2L)](https://github.com/d2l-ai/d2l-en) book.
The goal of this project is to better understand transformer myself，simplify the original implementation for beginners
and provide a clearer context for each component.

## 📌 Key Features
- **Rewritten Transformer Core**: Multi-Head Attention, Encoder and decoder modules are implemented from scratch
  based on my understanding, with references to the structure described in D2L and other
  public resources.
- **Simplified Code Structure**: The original D2L example involves multiple nested
  functions across files; here the logic is reorganized for easier navigation and learning.
- **Beginner-Friendly**: Designed for those who want to study the Transformer architecture
  without being overwhelmed by complex function dependencies.

## 🚀 Contents
- `Utilities` — CPU/GPU/Display related functions (Directly adapted from D2L example code)
- `Download Data` — Prepare the test Data (Directly adapted from D2L example code)
- `Basic Functions for Transformer` — Basic functions needed to be used in Transformer (Adapted from D2L example code and modified here)
- `Transformer` —Rewritten Transformer encoder and decoder implementation (Adapted from D2L example code and modified here)
- `Training and Prediction` — Train the model and make simple predictions (Directly adapted from D2L example code)

## 📚 References
- Vaswani et al., *Attention Is All You Need*, NeurIPS 2017.
- [Dive into Deep Learning (D2L)](https://github.com/d2l-ai/d2l-en)
- @mantis522, *Transformerとは？数学を用いた徹底解説：Encoder編*, https://qiita.com/mantis522/items/b45494f4378b066d0432
- xiaoh_7, *手撕Transformer！！从每一模块原理讲解到代码实现【超详细！】*, https://blog.csdn.net/xiaoh_7/article/details/140019530

## ⚠️ Disclaimer
This project is for educational purposes only. It is **not** optimized for production use. 
Any mistakes or deviations from the original Transformer implementation are my own.

## 📝 License
This project is released under the MIT License.

**Third-Party Notices**  
Parts of the data downloading/preparation scripts and training/evaluation code are
adapted from the Dive into Deep Learning (D2L) project, licensed under a modified MIT License.

Original copyright:
Copyright 2019 Amazon.com, Inc. or its affiliates. All Rights Reserved.

