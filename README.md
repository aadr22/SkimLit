# SkimLit: Research Abstract Classification
## Overview
SkimLit is a Natural Language Processing (NLP) project designed to classify sections of medical research abstracts into categories such as Background, Methods, Results, and Conclusions. Inspired by the PubMed 200k RCT dataset methodology, this project aims to streamline the process of reading and organizing medical literature. The model achieved an accuracy improvement from 72.18% (baseline) to 83.04%, representing a relative performance increase of approximately 15%.

## Features
- Dataset: Utilizes the PubMed 200k RCT dataset for training and evaluation, consisting of labeled medical abstracts.
- Data Preprocessing:
    Tokenization and text cleaning for structured input.
    Conversion of abstract sentences into embeddings for model input.
- Model Architecture:
    Implements a tribrid embedding approach combining token, character, and positional embeddings.
    Leverages deep learning architectures inspired by cutting-edge NLP research.
- Training Tools: Includes callbacks like learning rate schedulers and TensorBoard visualization for monitoring training progress.

## Results
The model achieves:
- Accuracy: Improved from 72.18% to 83.04%, showcasing significant gains in classification performance.
- Demonstrates robust capability to classify abstract sections accurately for medical literature.
  
## How to Use
1) Clone this repository and ensure TensorFlow (v2.4+) is installed.
2) Run the provided notebook to:
    Preprocess the PubMed 200k RCT dataset.
    Train the tribrid embedding model on labeled abstracts.
    Use the trained model to classify new research abstracts into predefined categories.
