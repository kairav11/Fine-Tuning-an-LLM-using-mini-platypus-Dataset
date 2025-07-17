# Fine-Tuning-an-LLM-using-mini-platypus-Dataset
This project demonstrates the process of fine-tuning a pre-trained Large Language Model (LLM) using QLoRA, and provides a simple interface to compare model responses before and after fine-tuning. It is built and tested in a Kaggle notebook environment using Hugging Face Transformers and  TRL libraries. Google Collab notebook can be found [here](https://colab.research.google.com/drive/1lKfJovB2zhcnSuQWWrVJGHxc4m71uX2D?usp=sharing) 

# Project Overview
Steps followed:
1. Load a pre-trained LLM using parameter-efficient fine-tuning (quantized Low-Rank adaptation QLORA). LLM used : [TinyLlama 1.1B Chat v1.0](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0)
2. Fine-tune the model on a custom dataset. Dataset used : [mini-platypus](https://huggingface.co/datasets/mlabonne/mini-platypus)
3. Generate responses from the model before and after training.
4. Display and compare the outputs across multiple prompts in a clear table format.

## Further Improvements 
1. Create a better UI.
2. Compare evaluation metrics.
3. Get a better GPU subscription to improve the model and fine tuning. A lot of optimizations were made for the code to run easily on the free version. :(

