# Wikipedia Dataset Fine-Tuning with QLoRA

This project focuses on preprocessing the Wikipedia dataset and fine-tuning large language models (LLMs) using the QLoRA technique for efficient low-rank adaptation on big datasets.

## Project Overview

- **Data Preprocessing**:  
  - Cleaned and tokenized Wikipedia data to prepare it for model fine-tuning.
  - Handled large-scale data efficiently for training LLMs.

- **Model Fine-Tuning**:  
  - Leveraged the **QLoRA (Quantized Low-Rank Adaptation)** technique to fine-tune large language models on massive datasets with limited GPU memory.
  - Supports efficient training while maintaining high model performance.

## Features

- Efficient preprocessing pipeline for large textual datasets.
- Low-rank adaptation fine-tuning with quantization for memory efficiency.
- Ready for further experimentation with LLMs on downstream NLP tasks.

## Installation

```bash
git clone <your-repo-url>
cd wikipedia-qlora-finetune
pip install -r requirements.txt
