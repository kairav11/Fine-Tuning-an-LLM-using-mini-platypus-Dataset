# Fine-Tuning-an-LLM-using-mini-platypus-Dataset
This project demonstrates the process of fine-tuning a pre-trained Large Language Model (LLM) using QLoRA, and provides a simple interface to compare model responses before and after fine-tuning. It is built and tested in a Google Collab notebook environment using Hugging Face Transformers and  TRL libraries. Google Collab notebook can be found [here](https://colab.research.google.com/drive/1lKfJovB2zhcnSuQWWrVJGHxc4m71uX2D?usp=sharing) 

# Project Overview
Steps followed:
1. Load a pre-trained LLM using parameter-efficient fine-tuning (quantized Low-Rank adaptation QLORA). LLM used : [TinyLlama 1.1B Chat v1.0](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0)
2. Fine-tune the model on a custom dataset. Dataset used : [mini-platypus](https://huggingface.co/datasets/mlabonne/mini-platypus)
3. Generate responses from the model before and after training.
4. Display and compare the outputs across multiple prompts in a clear table format.

## Further Improvements 
1. Add Quantitative Evaluation Metrics like BLEU, ROUGE, or exact match scores on a held-out validation set for measuring performance before and after fine-tuning.
2. Integrate FAISS for Semantic Search + Matching Logic.
3. Feedback Loop with Reward Modeling (RLAIF-style).
4. Inference API or Streamlit Demo.
5. Memory & Logging System.
6. Upgrade existing GPU resources.



