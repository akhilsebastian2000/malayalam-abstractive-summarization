# Malayalam Abstractive Summarization

## Project Overview

This project focuses on **Malayalam Abstractive Text Summarization** using multiple Transformer-based language models. The objective is to generate concise and meaningful Malayalam summaries while comparing different approaches such as **Zero-Shot Learning, Few-Shot Learning, Fine-Tuning, and Retrieval-Augmented Generation (RAG)**.

The project also evaluates the generated summaries using automatic evaluation metrics and analyzes challenges such as **hallucination** and faithfulness.

---

## Models Used

The project includes experiments using the following Transformer-based models:

- mT5
- mBART
- BLOOMZ
- Sarvam

---

## Approaches Implemented

### 1. Zero-Shot Learning

Models generate Malayalam summaries without task-specific training.

Experiments are organized in:

```text
zero_shot/
