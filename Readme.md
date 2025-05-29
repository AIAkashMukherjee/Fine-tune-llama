# Sentiment Classification with LLaMA-2 Fine-tuned on Stanford Sentiment Dataset

This repository contains code and model weights for a sentiment classification task fine-tuned on the [Stanford Sentiment Dataset](https://huggingface.co/datasets/PhilSad/standfordsentiment) using the `NousResearch/Llama-2-7b-chat-hf` model.

## Overview

- **Dataset:** Stanford Sentiment Dataset (`PhilSad/standfordsentiment`)
- **Base Model:** `NousResearch/Llama-2-7b-chat-hf`
- **Task:** Sentiment classification (labels: positive, neutral, negative)
- **Fine-tuning:** Using supervised fine-tuning with Hugging Face's Trainer and PEFT (Parameter-Efficient Fine-Tuning)
- **Inference:** Predict sentiment label from input text

## Setup Instructions

### Requirements

- Python 3.8+
- PyTorch
- Transformers
- Datasets
- Accelerate
- PEFT
- Tokenizers
