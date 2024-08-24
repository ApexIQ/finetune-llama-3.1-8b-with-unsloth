# Finetuning Llama-3.1 8b Conversational + Unsloth 2x faster

This repository contains a Jupyter Notebook for fine-tuning the Llama 3.1 8B model using the **unsloth** library.

## Overview

The **Llama 3.1** model is a powerful multilingual large language model designed for various natural language processing tasks. This notebook demonstrates how to fine-tune the model efficiently using the **unsloth** library, which allows for faster training and reduced memory usage.

## Features

- Fine-tune the Llama 3.1 8B model on custom datasets.
- Utilize LoRA (Low-Rank Adaptation) for efficient training.
- Save and export the fine-tuned model for deployment.

## Requirements

- Python 3.x
- Jupyter Notebook
- GPU with at least 16GB VRAM
- Unsloth library

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone git@github.com:ApexIQ/finetune-llama-3.1-8b-with-unsloth.git
   cd <repository-directory>
   ```

2. **Open the notebook**:
   Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Then open the `fine_tune_llama.ipynb` file.

3. **Run the cells**: Follow the instructions in the notebook to fine-tune the model.

## About Unsloth

**Unsloth** is a library that enhances the fine-tuning process for large language models like Llama 3.1. It enables:

- Up to 2x faster training times.
- 60% less memory usage compared to traditional methods.
- Support for various model formats for easy deployment.
