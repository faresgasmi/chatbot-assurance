AI Chatbot for MAGHREBIA Home Insurance

This project is an AI chatbot designed to help users understand the home insurance services offered by MAGHREBIA, a Tunisian insurance company.

The chatbot uses Retrieval-Augmented Generation (RAG) with FAISS and a local AI model (Ollama) to answer user questions using information extracted from insurance documents.

The goal is to provide clear and helpful answers about home insurance coverage, guarantees, and services.

🚀 Features

🤖 AI chatbot specialized in MAGHREBIA home insurance

🔎 Semantic search using FAISS vector database

🧠 AI responses generated with Ollama (LLaMA models)

📄 Document processing and text chunking

⚡ Fast retrieval of relevant insurance information

⚙️ How It Works

The main insurance document is processed and divided into smaller sections.

Each section is split into text chunks.

These chunks are converted into vector embeddings using Sentence Transformers.

The embeddings are stored in a FAISS index.

When a user asks a question:

The system searches for the most relevant chunks.

The AI model uses this context to generate a response.

This approach ensures that answers are based on real company information.

🛠 Technologies Used

Python

Sentence Transformers

FAISS (Vector Search)

Ollama (Local LLM)

Retrieval-Augmented Generation (RAG)

📁 Project Structure
project/
│
├── assurance_complet.txt
├── data/                  # Structured insurance documents
├── chunks/                # Text chunks used for RAG
├── chatbot_rag.py         # Chatbot script
├── embeddings.faiss       # Vector database
└── README.md
💬 Example

User question

Does MAGHREBIA home insurance cover theft?

Chatbot answer

Yes. The home insurance policy includes protection against theft,
such as burglary, forced entry, and damage caused during a theft.
📌 Goal of the Project

This project demonstrates how to build a domain-specific AI assistant using modern AI tools such as RAG, vector databases, and local LLMs.

It shows how AI can help improve customer support and information access in the insurance sector.

⭐ If you like this project, feel free to give it a star on GitHub!

✅ Si tu veux, je peux aussi te faire une version encore meilleure pour impressionner les recruteurs (stage / AI engineer) :

plus professionnelle

toujours courte

avec diagramme architecture RAG.
