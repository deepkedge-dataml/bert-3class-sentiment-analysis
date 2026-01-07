# BERT 3-Class Sentiment Analysis

This project implements a **BERT-based sentiment classification model** to categorize text into **positive, neutral, and negative** classes.

## Overview
- Dataset size: ~701k samples
- Model: `bert-base-uncased`
- Task: 3-class sentiment classification
- Framework: Hugging Face Transformers

## Methodology
- Text cleaning and validation
- Tokenization using BERT tokenizer (CPU-based)
- Fine-tuning BERT using `Trainer`
- Evaluation using accuracy, precision, recall, F1-score
- Confusion matrix and sample-level probability analysis

## Results
- Accuracy: ~89–90%
- Macro F1-score: ~0.89

## Notes
- Training performed once (~1h 20m on GPU)
- Notebook is structured for clarity and reproducibility
- Focus is on evaluation and error analysis

