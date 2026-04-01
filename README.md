
# SmartFAQ 🤖

An intelligent Frequently Asked Questions (FAQ) system that leverages advanced NLP techniques to automatically retrieve and answer user queries from a large corpus of product Q&A data.

## 📋 Overview

SmartFAQ is a Jupyter Notebook-based project that demonstrates how to build a semantic search-powered FAQ system. It uses **Sentence Transformers** and **FAISS** (Facebook AI Similarity Search) to understand user queries at the semantic level and return the most relevant answers from a database of real product questions and answers.

### Key Features

- **Semantic Search**: Utilizes state-of-the-art sentence embedding models to understand query intent beyond keyword matching
- **Fast Retrieval**: Powered by FAISS for efficient similarity search over large datasets
- **Real-World Data**: Trained on Amazon product Q&A data (85,865+ question-answer pairs)
- **Text Preprocessing**: Includes NLP pipelines for cleaning and normalizing text data
- **Scalable Architecture**: Can be deployed with Streamlit for interactive use

## 🎯 Use Cases

- E-commerce product support automation
- Customer service FAQ automation
- Knowledge base retrieval systems
- Question answering systems for product catalogs

## 📊 Dataset

The project uses the **Amazon Top Cell Phones and Accessories Q&A Dataset** from Kaggle:

- **Total Records**: 85,865 Q&A pairs
- **Columns**: questionType, question, answer, answerType, answerTime, ASIN, etc.
- **Question Types**: Yes/No, Open-ended
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/validmodel/amazon-top-cell-phones-and-accessories-qa)

## 🚀 Quick Start

### Prerequisites

```bash
pip install -q colab-xterm kaggle sentence-transformers faiss-cpu scikit-learn pyngrok streamlit nltk transformers datasets peft accelerate bitsandbytes
