Overview
A simple Generative AI chatbot built using React for the frontend and Node.js/Express for the backend. The project demonstrates how GenAI features like embeddings, semantic search, and RAG can be integrated into a clean chat interface.
Features
• Modern React-based chatbot UI
• Sidebar navigation with New Chat and History
• Chat window with streaming-style responses
• Node.js/Express backend for message handling
• Easy integration with OpenAI, Gemini, or custom Python model
• Supports future expansion into RAG or vector DB pipelines

GenAI Concepts Used
• Embeddings: User messages can be converted into vector representations for similarity matching, intent detection, or semantic search.
• Vector Databases: Enables storing and retrieving embedding vectors to provide context-aware answers.
• Semantic Search: Improves chatbot accuracy by retrieving the most relevant information based on meaning rather than keywords.
• RAG (Retrieval-Augmented Generation): Enhances LLM responses by adding retrieved context from documents, PDFs, or databases.

Tech Stack
Frontend: React
Backend: Node.js + Express
AI Engine: OpenAI API
Styling: CSS
Runtime: Browser + Node.js

Installation
Frontend: npm install → npm start
Backend: npm install → npm run dev
Environment: add API keys in .env


How It Works
User enters a message in the chat UI.
Message is sent to Node backend via API.
Backend forwards the message to an LLM or Python AI service.
Response is returned and displayed in chat.