# StudyAssist AI: LLM-powered Customer Support Automation

## 📌 Project Overview
This project implements an **AI-powered Q&A system** for an e-learning platform with **20,000+ paid students** and **180,000+ total students**. It leverages **Large Language Models (LLMs)** to automate responses to course-related queries, significantly reducing manual workload and response times.

### 🚀 Features
- **Automated Query Handling:** Uses LangChain and Google PaLM to provide instant responses.
- **Vector Similarity Search:** FAISS-based retrieval system for accurate answers.
- **Embeddings:** Uses Hugging Face Instructor Embeddings for improved understanding.
- **User-Friendly Interface:** Built with Streamlit for seamless interaction.
- **Efficient Customer Support:** Reduces response time from hours to seconds with **90%+ accuracy**.

---

## 🏗️ Technical Implementation
### 🔹 Data Source
- CSV file containing **Q&A pairs** from real student inquiries.

### 🔹 Architecture
1. **Data Processing:** CSVLoader to extract and structure data.
2. **Embedding Generation:** Uses **Hugging Face Instructor Embeddings**.
3. **Vector Database:** FAISS for **efficient similarity search**.
4. **LLM Processing:** Google **PaLM** for natural language understanding.
5. **Query Retrieval:** Implemented with LangChain’s **RetrieverQA** module.
6. **Frontend:** **Streamlit** for an interactive UI.

---

## 📌 Tech Stack

| Tech Stack | Description |
|------------|------------|
| ![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python) | Core language for backend processing |
| ![LangChain](https://img.shields.io/badge/LangChain-%230099FF.svg?style=for-the-badge) | Framework for LLM orchestration |
| ![Google PaLM](https://img.shields.io/badge/Google%20PaLM-AI-red?style=for-the-badge) | Large Language Model for generating responses |
| ![FAISS](https://img.shields.io/badge/FAISS-Vector%20Database-green?style=for-the-badge) | Used for similarity search and retrieval |
| ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Embeddings-yellow?style=for-the-badge&logo=huggingface) | Embeddings to enhance text representation |
| ![Streamlit](https://img.shields.io/badge/Streamlit-UI-red?style=for-the-badge&logo=streamlit) | Frontend for interacting with the system |
| ![CSVLoader](https://img.shields.io/badge/CSVLoader-Data%20Extraction-orange?style=for-the-badge) | Loads and structures the CSV dataset |
| ![RetrieverQA](https://img.shields.io/badge/RetrieverQA-LangChain-brightgreen?style=for-the-badge) | Efficient retrieval of relevant Q&A pairs |

---
