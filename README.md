# StackOverflow Tag Prediction using FastAI ULMFiT

This project leverages **FastAI's ULMFiT (Universal Language Model Fine-tuning)** with an **AWD-LSTM** architecture to classify StackOverflow questions into relevant tags.

## 🚀 Project Overview

- Fine-tuned a pre-trained language model using FastAI's ULMFiT and AWD-LSTM to predict tags for 20,000 StackOverflow questions.
- Achieved significant improvements by reducing validation loss by ~22% and decreasing perplexity from 199.8 to 60.5 over 5 epochs.
- Implemented gradual unfreezing, discriminative fine-tuning, and robust data preprocessing pipelines to optimize classification accuracy.

## 🛠️ Technologies and Libraries

- **FastAI** – Language modeling and classification (ULMFiT)
- **PyTorch** – Deep learning model implementation
- **Pandas** – Data handling and manipulation
- **Scikit-learn** – Data splitting and validation

## 📈 Results Summary

| Metric             | Before Tuning | After Tuning |
|--------------------|---------------|--------------|
| Validation Loss    | 5.29          | 4.10         |
| Perplexity         | 199.8         | 60.5         |
