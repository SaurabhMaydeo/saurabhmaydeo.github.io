---
layout: page
title: Disaster Tweet Classification
description: NLP model using BERT to classify disaster-related tweets
img: assets/img/project_nlp.jpg
importance: 2
category: nlp
---

## Overview

Built a natural language processing model to classify tweets into disaster and non-disaster categories, enabling rapid identification of emergency situations from social media.

## Technical Details

- **Technologies:** Python, TensorFlow, Hugging Face Transformers
- **Model:** BERT (Bidirectional Encoder Representations from Transformers)
- **F1 Score:** 80.90%

## Approach

1. **Text Preprocessing:** Cleaned tweets, handled URLs, mentions, and hashtags
2. **Tokenization:** Used BERT tokenizer for subword tokenization
3. **Fine-tuning:** Fine-tuned pre-trained BERT on the disaster classification task
4. **Evaluation:** Used F1 score as primary metric due to class imbalance

## Results

The BERT model achieved an F1 score of 80.90%, demonstrating strong performance in distinguishing genuine disaster reports from figurative language.

## Applications

This model can be used by:
- Emergency response teams for real-time disaster monitoring
- News organizations for breaking news detection
- Government agencies for crisis management
