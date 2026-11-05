
# LLM-Powered Supply Chain Risk Detection

## Project Overview

This project investigates whether transformer-based
text embeddings improve supply chain delivery-risk
prediction compared with traditional machine learning.

Course: DSC624 - Natural Language Processing and
Large Language Models

## Dataset

DataCo SMART Supply Chain Dataset

Source:
https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

Experiment sample: 12,000 records.

## Models Compared

1. Numeric-only Random Forest (baseline)
2. Numeric + TF-IDF
3. Numeric + Transformer Embeddings

## Experimental Results

| Model | Accuracy | F1-score |
|---|---|---|
| Numeric-only | 70.04% | 0.6742 |
| Numeric + TF-IDF | 68.50% | 0.6681 |
| Numeric + Transformer | 69.50% | 0.6839 |

The transformer model achieved a modest F1 improvement,
but the bootstrap confidence interval includes zero.

## How to Reproduce

1. Download the DataCo dataset from the link above.
2. Open DSC624_Task2_Google_Colab.ipynb in Google Colab.
3. Install the dependencies using the notebook's
   installation cell.
4. Follow the notebook's dataset loading instructions.
5. Use the same sample size, random seed, split,
   and model configuration as the original experiment.
6. Run all notebook cells in order.
7. Compare the generated metrics with results/.

## Outputs

- Model comparison metrics
- Confusion matrices
- Performance comparison charts
- Experimental report

## Reproducibility Notes

The dataset is not included in this repository.
Download it from the original source.

The notebook includes the preprocessing,
training, evaluation and embedding generation steps.
