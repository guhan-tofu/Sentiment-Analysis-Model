# Sentiment Analysis with BERT

This repository contains a Jupyter notebook that demonstrates how to build and fine-tune a **Sentiment Analysis** model using **BERT (Bidirectional Encoder Representations from Transformers)**. The notebook walks through the entire process, including data preparation, model setup, training, and evaluation.

## Overview

The notebook is designed to perform sentiment analysis on a text dataset. It uses the pre-trained BERT model from Hugging Face's `transformers` library and fine-tunes it on a labeled dataset to predict whether a given text expresses a positive or negative sentiment.

### Key Features:
- **Data Preprocessing:** Tokenization of text data using BERT tokenizer.
- **Model Architecture:** Fine-tuning a pre-trained BERT model for classification.
- **Training & Evaluation:** Model training, validation, and evaluation with accuracy and loss metrics.

## Dependencies

To run the notebook, you'll need the following Python packages:

- `transformers`
- `torch`
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install these dependencies by running:

```bash
pip install transformers torch pandas numpy scikit-learn matplotlib seaborn
