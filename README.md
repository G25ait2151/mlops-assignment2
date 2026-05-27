# MLOps Assignment 2

This project fine-tunes `distilbert-base-cased` for Goodreads book review genre classification using a Kaggle GPU notebook. The workflow uses Hugging Face Transformers for model training, Weights & Biases for experiment tracking and artifact logging, and Hugging Face Hub for model deployment. Please check the notebook in kaggle.

## Setup

Install dependencies:

```bash
pip install -r requirements.txt

In Kaggle, enable Internet and GPU accelerator. Add these Kaggle Secrets:

WANDB_API_KEY
HF_TOKEN
Then run the notebook end-to-end.

Results
Metric	Score
Accuracy	0.5950
F1 Score	0.5913
Eval Loss	2.2826
Links
Kaggle Notebook: https://www.kaggle.com/code/g25ait2151/notebook7d366c974f
Hugging Face Model: https://huggingface.co/G25AIT2151/distilbert-goodreads-genres
W&B Dashboard: https://wandb.ai/g25ait2151-indian-institute-of-technology-jodhpur/mlops-assignment2
