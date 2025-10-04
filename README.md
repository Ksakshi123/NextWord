# Next Word Prediction Using LSTM Model

Predict the next word in a sentence using a **Long Short-Term Memory (LSTM)** model.  
This project utilizes **Natural Language Processing (NLP)** and **Deep Learning** techniques to provide accurate word predictions.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
---

## Project Overview
This project aims to develop an **LSTM-based model** that predicts the next word in a sentence.  
The model is trained on a dataset containing a large collection of text data, enabling it to learn patterns and relationships within the language.  
It can be used for **autocomplete systems, text generation, and predictive typing applications**.

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/Ksakshi123/NextWord.git
cd next-word-prediction
```
2. Install the required libraries:
```bash
pip install -r requirements.txt
```
## Usage

Run the Jupyter Notebook next_word_prediction.ipynb to:

1. Preprocess the data

2. Build and train the LSTM model

3. Generate next-word predictions

## Dataset

The dataset used for training consists of articles, books, and web content.

Preprocessing includes:

1. Cleaning text and removing noise

2. Tokenization

3. Creating sequences for training

The vocabulary is built from the preprocessed dataset to train the model effectively.

## Model Architecture

The LSTM model is a type of Recurrent Neural Network (RNN) designed for sequence data.
3It captures long-range dependencies and patterns within text sequences.

Architecture:

1. Embedding Layer: Converts words into dense vectors

2. LSTM Layers: Learn sequential patterns and context

3. Dense Layer: Predicts the next word using softmax activation

## Results

The model is evaluated using metrics such as:

1. Accuracy of predicted words

2. Perplexity for language modeling

## Sample Output:

Seed Text: "Mr. Holmes"

Generated Text:

Mr. Holmes placed himself in a nature such as his activity however
