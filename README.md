# 🤖 Custom Question Answering using Transformers

This project implements a **custom question-answering system** using Transformer-based models such as BERT. It allows users to input a paragraph or context and then ask questions to extract precise answers, just like a mini search engine for your own data.

---

## 📚 Overview

The project uses **pretrained Transformer models** from the HuggingFace `transformers` library to answer questions based on user-provided context. It is ideal for:

- Extractive QA tasks
- Chatbot backends
- Domain-specific document QA systems

---

## 🧠 Technologies Used

- Python 🐍
- HuggingFace Transformers 🤗
- Tokenizers (BERT tokenizer)
- PyTorch or TensorFlow (depending on selected model)
- Streamlit (optional for UI)

---

## 🔍 How It Works

1. The user provides a **context** (paragraph or passage).
2. A **question** is asked about the context.
3. The model processes both using a Transformer architecture.
4. The system returns the most likely **answer span** from the context.

---

Context:
"India is the seventh-largest country by area, the second-most populous country, and the most populous democracy in the world."

Question:
"What is the rank of India by area?"

Answer:
"seventh-largest"


