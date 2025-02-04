# Encoder Is All You Need

## Overview
This project implements the Transformer **Encoder** from the paper ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762) using **PyTorch**. The goal is to compute self-attention for multiple heads, combine attention scores, and process sequences efficiently. This implementation is specifically designed for **sentiment analysis** on the **IMDB dataset**.

## Features
- ✅ Multi-Head Self-Attention
- ✅ Positional Encoding
- ✅ Layer Normalization
- ✅ Feedforward Networks
- ✅ Scaled Dot-Product Attention
- ✅ Sentiment Classification
- ✅ Configurable Hyperparameters


## 📊 Dataset
This project uses the **IMDB movie reviews dataset** for sentiment analysis. The dataset consists of **50,000 reviews**, labeled as either positive or negative.

You can download the dataset using:
```python
from torchtext.datasets import IMDB
train_iter, test_iter = IMDB()
```

## 📚 References
- 📄 [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- 🖼️ [Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
- 🎬 [IMDB Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)

---
💡 **For any issues, feel free to open an [issue](https://github.com/yourusername/encoder-is-all-you-need/issues) or contribute!** 🚀
