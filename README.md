
# 🧠 Text Generation & Emotion Classification with LSTM and Transformer Models

This project explores neural language modeling through two architectures—LSTM and Transformer—using PyTorch. It also extends the task from text generation to emotion classification using the `DailyDialog` dataset.

## 🎯 Objective

- Train LSTM and Transformer models to learn language generation patterns.
- Fine-tune and evaluate these models on emotion classification using labeled conversational data.

## 🧰 Features

- Language modeling using:
  - Long Short-Term Memory (LSTM)
  - Transformer-based sequence models
- Input batching and sequence generation using PyTorch utilities
- Emotion classification with the `DailyDialog` dataset
- Metrics: Loss (for generation) and Accuracy (for classification)
- Model comparison and GPU-accelerated training (Colab-compatible)

## 🧪 Tasks Performed

- Batch and tokenize input data
- Train LSTM and Transformer models on dialogue text
- Generate predictions for next-token or emotion classification
- Evaluate classification accuracy at sentence boundaries (`__eou__` tokens)

## 📦 Dependencies

- torch
- torchtext
- numpy
- Google Colab (recommended for GPU usage)

## 📁 File Structure

- `Homework1B.ipynb`: Main notebook with code for both generation and classification tasks
- `README.md`: Overview and instructions

## 🖥️ Credits

- Project based on UCSB ECE 157B/272B coursework
- Notebook created by Min Jian Yang and Matthew Dupree
- Inspired by PyTorch and KDnuggets tutorials
