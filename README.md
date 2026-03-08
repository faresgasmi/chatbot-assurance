<h1>MAGHREBIA Insurance – AI Chatbot (RAG Project)</h1>
<h2>📝 Overview</h2>

This project builds an AI chatbot designed to help users understand MAGHREBIA home insurance services.

MAGHREBIA is a Tunisian insurance company that offers different types of insurance such as:

Auto insurance

Health insurance

Home insurance

This chatbot focuses mainly on home insurance, helping users ask questions and receive clear explanations about guarantees, options, and services.

The project combines Artificial Intelligence (AI) and Retrieval-Augmented Generation (RAG) to generate answers based on real insurance documents.

<h2>🚀 Key Features</h2>
<h3>Document Processing</h3>

The original insurance document is processed before being used by the AI:

Splitting the main document into structured sections

Cleaning and preparing the text

Dividing the text into smaller chunks

This makes the information easier for the AI to search and understand.

<h3>RAG (Retrieval-Augmented Generation)</h3>

The chatbot uses a RAG system to answer questions.

How it works:

The user asks a question

The system searches the most relevant text chunks

These chunks are sent to the AI model

The AI generates a clear answer using this context

This helps the chatbot give more accurate and reliable responses.

<h3>Vector Search with FAISS</h3>

The project uses FAISS to perform fast similarity search between questions and documents.

FAISS allows the system to:

Store document embeddings

Find the most relevant information quickly

Improve the quality of chatbot answers

<h3>Local AI Model with Ollama</h3>

The chatbot uses Ollama to run a local language model such as:

Llama 3

Llama 3.1

Running models locally provides:

Faster responses

Better privacy

No external API required

<h2>🛠 Technologies Used</h2>

<b>Python</b> – main programming language

<b>Sentence Transformers</b> – text embeddings

<b>FAISS</b> – vector similarity search

<b>Ollama</b> – local AI model execution

<b>RAG Architecture</b> – context-based AI responses

<h2>📊 Data Source</h2>

The chatbot uses internal documentation about MAGHREBIA home insurance, including:

Insurance guarantees

Optional services

Insurance packs

Assistance services

The information is processed and converted into vector embeddings to enable semantic search.

## <h2>📁 Project Structure</h2>
<pre>
├── assurance_complet.txt            # data_complet
├── data/                            # Processed insurance sections
├── chunks/                          # Text chunks used for RAG
├── chatbot_rag.py                   # Main chatbot script
├── README.md                        # Project documentation
</pre>

User:

What does the home insurance cover?

Chatbot:

MAGHREBIA home insurance protects your home against several risks such as:
- Theft
- Water damage
- Fire and electrical damage
- Natural events like storms
<h2>📌 Why This Project?</h2>

This project demonstrates how AI can be used to improve customer assistance in the insurance sector.

It shows the ability to:

Build a RAG chatbot

Process real business documents

Use vector search and embeddings

Deploy a local AI assistant

<h2>🌐 Connect With Me</h2>

📧 Email: faresguesmi815@gmail.com

💼 LinkedIn:
<a href="https://www.linkedin.com/in/fares-guesmi-6aa849262/">Fares Guesmi</a>

⭐ If you like this project, feel free to give it a star on GitHub!
