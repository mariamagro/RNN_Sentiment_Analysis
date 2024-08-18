# Sentiment Analysis Projects

This repository contains implementations of two distinct projects focusing on sentiment analysis with different neural network architectures.

**Credit:**
The implementation is based on tasks provided by Pablo M. Olmos.

**Completed by:**
- **Marina Gómez Rey** (https://github.com/MarinaGRey)
- **Ángela Durán**
- **María Ángeles Magro Garrote**

## Projects

### 1. Sentiment Analysis with RNNs

**Notebook:** [Sentiment_Analysis.ipynb](Sentiment_Analysis.ipynb)

**Description:**
This project involves building a sentiment analysis model using Recurrent Neural Networks (RNNs). The primary objective is to classify text into sentiment categories such as positive or negative based on the text content. The RNN model processes sequences of words and captures temporal dependencies, making it suitable for understanding context in textual data.

**Key Components:**
- **Data Preparation:** Involves preprocessing steps like tokenization, normalization, and padding to prepare text data for the RNN model.
- **Model Architecture:** Utilizes an RNN-based architecture for sentiment classification.
- **Training and Evaluation:** The model is trained on labeled data and evaluated based on performance metrics such as accuracy, precision, and recall.


### 2. RNNs for Sentiment Analysis with Attention

**Notebook:** [Sentiment_Analysis_with_Attention.ipynb](Sentiment_Analysis_with_Attention.ipynb)

**Description:**
This project builds upon the basic sentiment analysis model by incorporating an attention mechanism into the Recurrent Neural Network (RNN). The attention mechanism allows the model to focus on different parts of the input sequence, improving its ability to understand context and sentiment more accurately. This enhancement can lead to better performance compared to a standard RNN model.

**Key Components:**
- **Attention Mechanism:** Integrates an attention layer with the RNN to highlight important parts of the input sequence.
- **Model Architecture:** Employs an LSTM-based model with an attention mechanism for enhanced sentiment classification.
- **Training and Evaluation:** The enhanced model is trained and evaluated, with attention weights being visualized to understand the focus of the model.


