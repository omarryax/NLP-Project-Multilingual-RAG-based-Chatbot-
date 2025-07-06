# NLP-Project-Multilingual-RAG-based-Chatbot
# Multilingual NLP Chatbot using Sentence Embeddings & Pinecone

This project demonstrates a multilingual question-answering chatbot that works for both **English** and **Urdu** using modern NLP techniques.

It leverages:
- Pre-trained embedding models (DistilUSE, E5, BGE)
- Sentence chunking and vector storage in **Pinecone**
- Semantic search to retrieve relevant text chunks
- A generative model (FLAN-T5) to answer user queries

---

## 🚀 Features

- 🔤 Multilingual support: English 🇬🇧 and Urdu 🇵🇰
- 🤖 Semantic search using sentence embeddings
- ⚡ Fast retrieval with Pinecone vector database
- 🧠 Answer generation using FLAN-T5 (Google's T5 model)
- 📁 Chunking large text data for better contextual understanding

---

## 🛠️ Technologies Used

- Google Colab (for development)
- Python
- Sentence Transformers
- Pinecone (Vector DB)
- Hugging Face Transformers (FLAN-T5)
- JSON, NumPy, Matplotlib

---

## 🧪 How It Works

1. **Text Preprocessing**: Clean and chunk Urdu and English documents.
2. **Embedding**: Convert text chunks into dense vector representations using:
   - `distiluse-base-multilingual-cased-v1`
   - `intfloat/multilingual-e5-small`
   - `BAAI/bge-small-en-v1.5`
3. **Storage**: Upload all embeddings to Pinecone vector indexes.
4. **Querying**:
   - Encode the user’s query into a vector.
   - Perform similarity search in Pinecone.
   - Retrieve top-matching chunks.
5. **Answering**: Use FLAN-T5 to generate a contextual answer from the top chunks.

---

## 📸 Example Query

> **User:** What is the difference between AI and machine learning?

Bot:
> AI is the broader concept of machines being able to carry out tasks in a smart way, while ML is a subset focused on the idea that machines can learn from data.

---
## 👤 Author  **Muhammad Umar Riaz**  Feel free to connect or reach out!
