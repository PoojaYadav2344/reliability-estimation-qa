

# Reliability Estimation Framework for Question Answering Systems

This repository contains the implementation and experimental framework used for evaluating the reliability and uncertainty characteristics of transformer-based question answering (QA) systems under both answerable and unanswerable question settings.

- ## Dataset

The experiments were conducted using publicly available benchmark datasets:

- SQuAD v2.0:
  https://rajpurkar.github.io/SQuAD-explorer/

- QuAC:
  https://quac.ai/

Please download the datasets from their respective official sources and place them in the working directory before executing the notebooks.

## Evaluated Models
- BERT Base
- RoBERTa
- ALBERT
- DistilBERT

## Methodology
The framework includes:
- Monte Carlo Dropout (MCD)-based uncertainty estimation
- Input perturbation using paraphrasing

## Evaluation 
- Cosine similarity analysis
- F1 score evaluation
- Statistical analysis of prediction consistency


## Implementation Details
The experiments are implemented using:
- Hugging Face Transformers
- Sentence-BERT
- PyTorch
- Google Colab

This repository is intended to support reproducibility and transparency of the experimental methodology presented in the associated research study.# reliability-estimation-qa
