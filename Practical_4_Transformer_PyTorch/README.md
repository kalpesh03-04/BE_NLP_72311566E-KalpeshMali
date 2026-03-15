# 🧠 NLP Practical 4

## Implementation of Transformer using PyTorch

---

## 🎯 Objective

To understand the architecture of a **Transformer model** and implement a basic **Transformer using the PyTorch deep learning framework**.

---

## 📌 Problem Statement

Implement a **Transformer model using PyTorch** and demonstrate its functionality by passing sample input tensors through the model and observing the output.

---

## 🛠 Tools and Libraries

* Python
* Jupyter Notebook
* PyTorch

---

## 📚 Description

### 1️⃣ Transformer Architecture

The **Transformer** is a deep learning model introduced for handling sequential data.
Unlike traditional RNNs or LSTMs, Transformers use a mechanism called **Self-Attention** to process input sequences.

Key components of the Transformer include:

* Multi-Head Attention
* Feed Forward Neural Networks
* Encoder Layers
* Decoder Layers
* Layer Normalization
* Dropout

Transformers are widely used in **Natural Language Processing tasks** such as:

* Machine Translation
* Text Summarization
* Chatbots
* Language Modeling
* Question Answering

---

### 2️⃣ PyTorch Transformer Model

In this practical, the built-in **`nn.Transformer`** module from PyTorch is used.

The model contains:

* Encoder layers
* Decoder layers
* Multi-Head Attention mechanism
* Feed-forward neural network layers

Random input tensors are generated and passed through the transformer model to observe how the architecture processes sequential data.

---

## 📊 Implementation Steps

1. Install and import the PyTorch library.
2. Create a Transformer model using `nn.Transformer`.
3. Generate random source and target tensors.
4. Pass the tensors through the transformer model.
5. Observe the output tensor shape.

---

## 📷 Output

The following outputs are generated:

* Transformer model architecture
* Transformer output tensor shape

Screenshots of these outputs are included in this folder.

---

## ✅ Conclusion

The Transformer model is a powerful deep learning architecture that uses **self-attention mechanisms** to process sequential data efficiently.
Using PyTorch, we implemented a basic transformer and verified its functionality by generating output from sample input tensors.
