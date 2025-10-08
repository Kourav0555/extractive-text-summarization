# Extractive Text Summarization using a Sigmoid Neuron

## Project Overview
This mini-project demonstrates **extractive text summarization** using a single Sigmoid Neuron in Python. 
The model assigns importance scores to sentences and selects the top ones to generate a concise summary.

## Workflow
1. Input text is split into sentences.
2. Sentences are converted into numerical features using **TF-IDF**.
3. A **Sigmoid Neuron** scores each sentence:  
   `score = sigmoid(weight * feature + bias)` (weights & bias randomly initialized).
4. The **top N sentences** are selected to form the final summary.

## Key Learnings
- Understanding **sigmoid activation** in deep learning.
- Importance of **feature extraction (TF-IDF)** for model performance.
- Difference between **extractive vs. abstractive summarization**.
- Hands-on implementation using **Python & NumPy**.

## Tech Stack
- Python
- NumPy
- scikit-learn
- Google Colab (optional)
