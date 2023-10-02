# Question Answering on Mathematics Dataset

Deep Learning (NLP) project on the implementation of a Question Answering model on  Mathematics Dataset.

## Details
The project I developed aims to solve the interesting task of question answering on a dataset containing mathematics questions and answers in a free-form textual input/output format at roughly school-level difficulty. The task is challenging because the mixed input format of the questions, for example 
```
Solve 24 = 1601*c - 1605*c for c.
```
requires a deep knowledge and understanding of symbol rules, mathematics laws and axioms that are not easy to learn and to generalize without any basic knowledge. In this project paper I will explain what I implemented to solve this demanding task: one simple baseline method, an additional baseline method and the State-of-the-Art approach.

## Dataset
Mathematics Dataset (https://huggingface.co/datasets/math_dataset)

## Language, libraries and frameworks
Python, pytorch, pytorch-lightning

## Approaches
1. First baseline: LSTM
2. Additional baseline: Transformer
3. State-of-The-Art approach: TP-Transformer

NB.: The codes for the Transformer and TP-Transformer architectures have not been re-implemented from scratch; rather, they have been taken from the official source codes. Nevertheless, I have acquired substantial knowledge from this project through a comprehensive examination of the Transformer's architecture.