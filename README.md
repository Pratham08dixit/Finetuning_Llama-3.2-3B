# Fine-tuning LLaMA-3.2:3B using Unsloth and QLoRA PEFT

This repository contains a Jupyter Notebook that demonstrates how to fine-tune the LLaMA-3.2:3B model using the Unsloth framework combined with QLoRA PEFT fine-tuning. This approach is designed for efficient and cost-effective model adaptation, leveraging parameter-efficient fine-tuning techniques.

## Overview

In this notebook, you will:
- **Set Up the Environment:** Install necessary libraries and load the pre-trained LLaMA-3.2:3B model.
- **Data Preparation:** Process and tokenize your dataset for training.
- **Fine-tuning with QLoRA:** Apply the QLoRA method via PEFT to fine-tune the model.
- **Evaluation & Saving:** Evaluate the model's performance and save the fine-tuned model for inference.

## Prerequisites

- **Python 3.8+**
- **Jupyter Notebook or Jupyter Lab**
- **GPU Resources:** A CUDA-enabled NVIDIA GPU is highly recommended for training.
- **Internet Connection:** Required for downloading model weights and datasets.
