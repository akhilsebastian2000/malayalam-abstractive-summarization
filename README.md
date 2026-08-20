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
```

---

### 2. Few-Shot Learning

Models are provided with example input-output pairs to guide summary generation.

Experiments are organized in:

```text
few_shot/
```

---

### 3. Fine-Tuning

Selected Transformer models are fine-tuned for the Malayalam abstractive summarization task.

Experiments are organized in:

```text
fine_tuning/
```

---

### 4. Retrieval-Augmented Generation (RAG)

Retrieval techniques are combined with language models to provide relevant context during summary generation.

Experiments are organized in:

```text
rag/
```

---

## Evaluation

The generated summaries are evaluated and compared using:

- ROUGE
- BLEU
- BERTScore

The evaluation also considers summary quality, faithfulness, and hallucination behavior.

Evaluation notebooks are available in:

```text
evaluation/
```

---

## Repository Structure

```text
malayalam-abstractive-summarization/
│
├── zero_shot/
│   └── Zero-shot summarization experiments
│
├── few_shot/
│   └── Few-shot summarization experiments
│
├── fine_tuning/
│   └── Fine-tuning experiments
│
├── rag/
│   └── Retrieval-Augmented Generation experiments
│
├── evaluation/
│   └── Model evaluation and comparison
│
├── malayalam-summarisation-project-2.ipynb
│
└── README.md
```

---

## Project Workflow

1. Prepare Malayalam text data for summarization.
2. Perform zero-shot experiments using multiple Transformer models.
3. Perform few-shot experiments using example-based prompting.
4. Fine-tune selected models for improved summarization.
5. Apply Retrieval-Augmented Generation (RAG).
6. Generate summaries using different models and approaches.
7. Evaluate generated summaries using ROUGE, BLEU, and BERTScore.
8. Compare model performance and analyze summary quality.

---

## Objective

The main objective of this project is to perform a comparative evaluation of different Transformer-based approaches for **Malayalam Abstractive Summarization** and analyze how zero-shot, few-shot, fine-tuning, and RAG approaches affect summary generation.

---

## Technologies Used

- Python
- Jupyter Notebook
- Hugging Face Transformers
- PyTorch
- mT5
- mBART
- BLOOMZ
- Sarvam
- Retrieval-Augmented Generation (RAG)
- ROUGE
- BLEU
- BERTScore

---

## Author

**Akhil Sebastian**

This repository contains the experimental notebooks and evaluation work developed as part of the Malayalam Abstractive Summarization project.
