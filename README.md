# AI News Summarizer & Content Generator

> An AI agent that automatically summarizes news articles and drafts engaging LinkedIn posts, turning current events into social content.

---

### The Business Problem

For any company, staying relevant and maintaining an active social media presence is a time-consuming challenge. Marketing and communications teams spend hours sifting through news, identifying relevant stories, and crafting content. This project was designed to automate that workflow.

### The Story Behind The Project

This project was developed as a take-home assignment for an AI Engineer internship interview. The challenge was to build a functional, high-performance RAG system that solved a real-world business problem in a limited time frame. This repository is the result of that successful challenge.

### The Technical Solution

This is a high-performance RAG system that combines multiple search techniques and an agent-based architecture to deliver polished, ready-to-use content.

*   **Core Function:** Ingests articles from the Kaggle News Dataset.
*   **Hybrid Retrieval:** Uses a combination of semantic search and keyword search to find the most relevant articles for a given topic.
*   **LLM-Powered Summarization:** A RAG pipeline generates concise, accurate summaries.
*   **Automated Content Creation:** A dedicated "LinkedIn Post Generator" agent transforms the news insights into a polished social media post.

### Tech Stack
*   **Core AI:** RAG, LangChain (or similar)
*   **NLP Features:** Named Entity Recognition (NER), Semantic Search
*   **Data Storage:** VectorDB (e.g., FAISS, Chroma)
*   **Environment:** Python, Jupyter Notebook
