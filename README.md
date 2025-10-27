
# 🧠 Tweet Classification using LSTM & Bi-LSTM

This project focuses on classifying tweets as **personal health mentions** or **non-personal health mentions** using deep learning techniques.  
The main goal is to build an **LSTM-based text classification model** that understands the context of each tweet to make accurate predictions.

---

## 📋 Project Overview

Social media platforms like Twitter contain massive amounts of text data related to health discussions.  
This project aims to automatically identify whether a tweet refers to a **personal health condition**, which can support **public health monitoring and analysis**.

The project involves:
- Text preprocessing and cleaning
- Tokenization and padding
- Building and training LSTM and Bi-LSTM models
- Evaluating performance on classification metrics

---

## 🚀 Key Features

- Implemented **LSTM** and **Bidirectional LSTM** models for sequential text analysis  
- Applied **Word Embeddings (Word2Vec/Embedding Layer)** for representing words in vector space  
- Preprocessed data using **tokenization**, **stopword removal**, and **padding sequences**  
- Achieved around **77–79% accuracy** on validation data  
- Built using **TensorFlow / Keras** and **Python**

---

## 🧰 Tech Stack

| Category | Technologies |
|-----------|---------------|
| Language | Python |
| Frameworks | TensorFlow, Keras |
| Libraries | NumPy, Pandas, Matplotlib, Scikit-learn |
| Environment | Google Colab / Jupyter Notebook |

---

## 🧩 Model Architecture

1. **Embedding Layer** – Converts words into dense vector representations  
2. **LSTM Layer** – Captures sequential dependencies in tweets  
3. **Dropout Layer** – Prevents overfitting  
4. **Dense Output Layer** – Sigmoid activation for binary classification  

You can also experiment with **Bidirectional LSTM** to capture both forward and backward context.

---

## 🧼 Data Preprocessing Steps

- Lowercasing text  
- Removing punctuation, numbers, and special characters  
- Removing stopwords  
- Tokenization and sequence padding  

---

## 📊 Results

| Model | Accuracy | Loss |
|--------|-----------|------|
| LSTM | ~77% | - |
| Bi-LSTM | ~79% | - |

🧑‍💻 Author

Yokitha R
📍 University of Peradeniya, Sri Lanka
💼 Aspiring AI & ML Intern
]

---


