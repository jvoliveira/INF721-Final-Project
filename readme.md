# INF721 Final Project 

## About the Project
This project aims to reproduce the sentiment classification experiments presented in the paper "Improving Language Understanding by Generative Pre-Training" by Alec Radford and collaborators (OpenAI, 2018). The paper highlights the use of a Transformer model pre-trained on unlabeled data, followed by fine-tuning for specific natural language understanding tasks.

The project focuses on:
- Implementing the model described in the paper.
- Reproducing the sentiment classification results using the Stanford Sentiment Treebank (SST-2).

## System Information
- **Operating System**: Windows
- **OS Version**: 10.0.19045
- **Architecture**: 64-bit
- **Processor**: Intel64 Family 6 Model 165 Stepping 3, GenuineIntel
- **Number of CPUs**: 12
- **Total Memory (GB)**: 15.87
- **GPU**: NVIDIA GeForce RTX 3060
- **GPU Memory Capacity (GB)**: 12.0
- **Number of GPUs Available**: 1

## Parameters
**Disclaimer**: The project was executed using a GPU (NVIDIA GeForce RTX 3060), and due to hardware limitations, some parameters had to be adjusted compared to the original paper. The following parameters were used:

- **Embedding size**: 768
- **Number of attention heads**: 12
- **Inner dimension**: 3072
- **Number of layers**: 12
- **Number of classes**: 2
- **Maximum sequence length**: 512
- **Batch Size:** 32
- **Pre-Train Epochs:** 100
- **Fine-tuning Epochs:** 3
- **Activation Function**: GELU (Gaussian Error Linear Unit).
- **Dropout:** 0.1

These adjustments were made to ensure the model could be trained with the available hardware resources and may affect the results compared to the original paper.


## Repository Structure
- `classification.ipynb`: Main file containing the project implementation.

## Prerequisites
Ensure the following dependencies are installed:

- Python 3.12.4 or higher
- Libraries: `torch`, `tokenizers`, `datasets`, `sklearn`, `os`

## How to Run

1. Install the dependencies listed above.
2. Adjust the hyperparameters as needed.
3. Start training by running the notebook.

## Expected Results
The goal is to reproduce the original paper's results in the sentiment classification task using pre-training.

## References
- Radford, Alec, et al. *Improving Language Understanding by Generative Pre-Training*. OpenAI, 2018. [Link](https://openai.com/research/language-unsupervised)
- [Stanford Sentiment Treebank (SST-2)](https://nlp.stanford.edu/sentiment)
- [Course INF721 Page](https://ufv-inf721-2024-2.lucasnferreira.com/)

