# LoRA Fine-Tuning using Keras

This repository demonstrates how to fine-tune a models like Gemma in Keras using Low-Rank Adaptation (LoRA). LoRA is a parameter-efficient fine-tuning technique that freezes the pre-trained model weights and injects trainable rank-decomposition matrices into each layer, significantly reducing the number of trainable parameters. :contentReference[oaicite:0]{index=0}

## Overview

Large Language Models (LLMs) like GPT-2 and Gemma are often over-parameterized for specific fine-tuning tasks. LoRA addresses this by introducing trainable low-rank matrices into each layer of the Transformer architecture, allowing for efficient fine-tuning without updating all model parameters. :contentReference[oaicite:1]{index=1}

In this repository, we apply LoRA to fine-tune the Gemma model using Keras. The process involves modifying the model architecture to include LoRA layers and training it on a specific dataset for a next-token prediction task.

## Repository Contents

- `LoRA_Tuning.ipynb`: A Jupyter Notebook that provides a step-by-step guide to implementing LoRA fine-tuning on the Gemma model using Keras. It covers data preprocessing, model modification, training, and evaluation.

## Getting Started

To get started with LoRA fine-tuning using Keras:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Rohit-Madhesiya/LoRA-Fine-Tuning-using-Keras.git
   cd LoRA-Fine-Tuning-using-Keras
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Notebook:**

  Open and run the `LoRA_Tuning.ipynb` notebook to perform the fine-tuning process.


**Author 👨‍💻**
**Developed by [Rohit Gupta]**
