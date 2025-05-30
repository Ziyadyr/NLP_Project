# Question Answering with DistilBERT on SQuAD 2.0
This repository contains code and instructions for fine-tuning the DistilBERT model (distilbert-base-uncased) on the SQuAD 2.0 dataset for the task of question answering.

## Project Overview
The goal of this project is to build a robust question answering (QA) system by fine-tuning a pretrained transformer model, DistilBERT, on the Stanford Question Answering Dataset (SQuAD) 2.0. The dataset includes questions that are answerable as well as unanswerable from a given context paragraph, making the task more challenging and realistic.

DistilBERT is a smaller, faster, and lighter version of BERT, making it a good choice for efficient QA applications.

## Dataset
SQuAD 2.0 combines the original SQuAD dataset with over 50,000 unanswerable questions written adversarially to look similar to answerable ones.

The model must predict both the span of the answer within the context or determine that no answer is available.

## Model
Base Model: distilbert-base-uncased

Fine-tuned for span prediction and answerability classification on SQuAD 2.0.

## Features
Data preprocessing and tokenization tailored for SQuAD 2.0.

Support for handling unanswerable questions.

Model saving .

## Requirements
Python 3.7+

Transformers library by Hugging Face

Datasets library by Hugging Face

evaluate library by Hugging Face

## Installation
git clone https://github.com/Ziyadyr/NLP_Project.git <br>
cd NLP_Project

## References
DistilBERT Paper: https://arxiv.org/abs/1910.01108

SQuAD 2.0 Dataset: https://rajpurkar.github.io/SQuAD-explorer/ 
                or https://huggingface.co/datasets/rajpurkar/squad_v2
