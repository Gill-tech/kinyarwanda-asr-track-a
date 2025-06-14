# kinyarwanda-asr-track-a

# 🇷🇼 Kinyarwanda ASR – Track A

This repository contains our solution for the **Kinyarwanda Automatic Speech Recognition (ASR) Hackathon – Track A**, hosted on Kaggle.

We develop an ASR model using mel spectrograms, character-level tokenization, and a GRU-based encoder-decoder trained with CTC loss.

## 📁 Structure

- `notebooks/` – Jupyter/Kaggle notebooks
- `models/` – GRU-based model and training logic
- `utils/` – Tokenizer, Dataset, Config files
- `train.py` – Optional script for local training
- `data/` – Placeholder (data comes from Kaggle competition)

## 🚀 Current Baseline

- Model: GRU encoder with CNN front-end
- Features: Mel spectrograms (128 dims)
- Loss: CTC
- Tokenizer: Character-based with special tokens

## 📊 Evaluation

We use the official metrics:

