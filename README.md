# GenAI Chatbot

## Overview
A simple Generative AI chatbot built using **React** for the frontend and **Node.js/Express** for the backend.  
The project demonstrates how GenAI features like **embeddings**, **semantic search**, and **RAG** can be integrated into a clean, modern chat interface.

## Features
- Modern React-based chatbot UI  
- Sidebar navigation with **New Chat** and **History**  
- Chat window with streaming-style responses  
- Node.js/Express backend for message handling  
- Easy integration with **OpenAI**, **Gemini**, or a custom Python AI model  
- Supports future expansion into **RAG** or **vector database** pipelines  

## GenAI Concepts Used
- **Embeddings:** User messages are converted into vector representations for **similarity matching**, **intent detection**, or **semantic search**.  
- **Vector Databases:** Store and retrieve embedding vectors to provide **context-aware responses**.  
- **Semantic Search:** Improves chatbot accuracy by retrieving the most relevant information based on **meaning**, rather than just keywords.  
- **RAG (Retrieval-Augmented Generation):** Enhances LLM responses by adding retrieved context from **documents**, **PDFs**, or **databases**.

## Tech Stack
- **Frontend:** React  
- **Backend:** Node.js + Express  
- **AI Engine:** OpenAI API  
- **Styling:** CSS  
- **Runtime:** Browser + Node.js  

## Installation
**Frontend:**  
```bash
npm install
npm start
````

**Backend:**

```bash
npm install
npm run dev
```

**Environment:**

* Add API keys in a `.env` file for the AI services you are using

## How It Works

1. User enters a message in the chat UI.
2. Message is sent to the Node.js backend via API.
3. Backend forwards the message to an LLM or Python AI service.
4. Response is returned and displayed in the chat window.

```