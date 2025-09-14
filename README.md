# Atyantik Chatbot (RAG-Based)

This project is a **Retrieval-Augmented Generation (RAG) chatbot** for Atyantik Technologies. The chatbot scrapes the company website, indexes relevant content using embeddings in **Qdrant**, and answers user queries in a **first-person company-representative style**. It provides informative, context-aware responses using a **large language model (OpenAI GPT-4.1)**.

---

## 🧩 Features

- Scrapes key pages from [Atyantik’s website](https://atyantik.com/).
- Extracts meaningful text and internal links recursively.
- Embeds documents using **OpenAIEmbeddings (text-embedding-3-large)**.
- Stores embeddings in **Qdrant** for vector search.
- Answers user queries based on retrieved context (RAG).
- Responds **as an official company chatbot** (first-person, informative).
- Simple MERN-compatible backend for chatbot integration.

---

## ⚙️ Tech Stack

- **Node.js** + **JavaScript**
- **LangChain** (Qdrant integration + Embeddings)
- **OpenAI API** (GPT-4.1 for response generation)
- **Qdrant** (Vector database for RAG)
- **Axios & Cheerio** (Web scraping)
- **React** (Basic frontend example included)
- Optional: **Docker** for Qdrant containerization



## 📁 Project Structure

