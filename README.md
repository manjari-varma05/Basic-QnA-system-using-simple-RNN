# 🧠 RNN-Based Question Answering System

A simple Natural Language Processing (NLP) project that uses a **Recurrent Neural Network (RNN)** to predict an answer token from a given question.

The project demonstrates the complete pipeline from text preprocessing and vocabulary creation to tokenization, word embeddings, RNN-based learning, and answer prediction.

---

## 🚀 Project Overview

The system takes a natural-language question as input and predicts the most likely answer word from a predefined vocabulary.
If the predicted probability is less than 0.5 then it outputs as 'Not exactly sure'

### Example

```text
Input:
What is the capital of France?

Output:
Paris
