# SC4002-NLP-Group-Project-G31

# Sentiment Classification with Pretrained Embeddings

## Overview
This project performs sentiment classification on the Rotten Tomatoes dataset using various deep learning models built on top of pretrained word embeddings. The project explores different model architectures and techniques to handle out-of-vocabulary (OOV) words. Each part of the assignment incrementally improves the model’s performance.

## Repository Structure
- **`base_embedding_matrix.pkl`**: Contains the initial embedding matrix with OOV words assigned to `<UNK>`.
- **`updated_embedding_matrix.pkl`**: Updated embedding matrix after applying OOV handling strategies.
- **`translations.json`**: Stores translations of OOV words to reduce redundant API calls to DeepL.
- **`part0-1_base.ipynb`**: Code for dataset preparation and base embedding setup.
- **`part0-1_oov.ipynb`**: Implements OOV handling strategies.
- **`part2_simpleRNN.ipynb`**: Implements a simple RNN model for sentiment classification.
- **`part3.1_simpleRNN.ipynb`** to **`**part3.5_multihead_attn_biGRU.ipynb**`**: Various enhancements, including updated embeddings, biLSTM/biGRU, CNN, and custom improvements.

## Requirements
Install the dependencies using:
```bash
pip install -r requirements.txt
