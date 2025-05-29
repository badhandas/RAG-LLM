# 📚 RAG-Based Interactive Learning with LLM

This project implements a **Retrieval-Augmented Generation (RAG)** system using a Large Language Model (LLM) to enable **interactive learning** from domain-specific content. Specifically, it uses lecture notes on **Pattern Recognition** from **FAU Erlangen-Nürnberg**, and stores them in a **Pinecone vector database** for efficient semantic search and retrieval.

## 🚀 Features

- ⚡ Retrieval-Augmented Generation using LLM
- 📘 Semantic search over FAU's pattern recognition lecture notes
- 💬 Interactive interface using Streamlit
- 🧠 Knowledge-aware response generation


📂 Data
- The project uses Pattern Recognition lecture notes from FAU Erlangen-Nürnberg, processed and embedded into a Pinecone vector store to enable semantic retrieval.

📦 Technologies Used
- 🧠 OpenAI or HuggingFace LLMs (configurable)
- 📁 Pinecone for vector storage
- 🛠️ Streamlit for front-end


🤝 Contributing
- We welcome contributions! Please feel free to submit pull requests, issues, or feature requests.


## 🛠️ Setup Instructions

Follow the steps below to get the project running locally:

## 1. Creating a Virtual Environment: You can create a virtual environment using the following command:
   ```bash
   python -m venv myenv
   ```
   
## 2. Install Requirements: Once you have the requirements.txt file, you can install the dependencies listed in it using pip:
   ```bash
   pip install -r requirements.txt
   ```
   
## 3. Start the application using
   ```bash
   streamlit run stream_lit.py
   ```
