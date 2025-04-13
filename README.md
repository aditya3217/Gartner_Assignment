# Book QA with RAG, FAISS & Knowledge Graph (Pride and Prejudice)

This project is a **Retrieval-Augmented Generation (RAG)** pipeline that allows users to ask questions about a book (default or user-provided), and get answers based on both **semantic chunk retrieval** (via FAISS) and **structured knowledge** (via RDF-based Knowledge Graph using `rdflib`).

---

##  Features

-  **Question Answering** on a book using OpenAI's GPT-4o-mini.
-  Supports **user-uploaded `.txt` files** or uses *Pride and Prejudice* from Project Gutenberg by default.
-  **Text chunking** with overlapping context using LangChain.
-  **FAISS Vector Store** for semantic similarity-based retrieval.
- **Knowledge Graph (RDFLib)** for structured relationships between entities (e.g. characters, places).
-  Streamlit-based **UI** to interact with the system in real-time.
-  Caching & persistent vector storage for faster reruns.

---

## 🧱 Tech Stack

- Python
- [OpenAI GPT-4o-mini](https://platform.openai.com/docs/guides/gpt)
- [Sentence Transformers (MiniLM)](https://www.sbert.net/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [LangChain Text Splitter](https://docs.langchain.com/docs/components/text_splitter/)
- [RDFLib](https://rdflib.readthedocs.io/)
- [Streamlit](https://streamlit.io/)

---

## 📂 Folder Structure

