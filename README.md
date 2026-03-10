<h1>MAGHREBIA Insurance AI Chatbot (RAG Project)</h1>

<h2>Overview</h2>

<p>
This project is an AI chatbot that helps users understand home insurance services offered by MAGHREBIA Assurances, a Tunisian insurance company.
</p>

<p>MAGHREBIA provides several types of insurance:</p>

<ul>
<li>Auto insurance</li>
<li>Health insurance</li>
<li>Home insurance</li>
</ul>

<p>
This chatbot focuses on home insurance. Users can ask questions and receive clear and simple explanations about insurance guarantees, options, and services.
</p>

<p>
The system uses Artificial Intelligence and <b>RAG (Retrieval-Augmented Generation)</b> to answer questions based on real insurance documents.
</p>

<h2>Project Features</h2>

<h3>Document Processing</h3>

<p>Before using the documents, the system processes the insurance text.</p>

<p>Steps:</p>

<ul>
<li>Split the main document into sections</li>
<li>Clean the text</li>
<li>Divide the text into smaller pieces called chunks</li>
</ul>

<p>
This makes the information easier to search and understand.
</p>

<h3>RAG (Retrieval-Augmented Generation)</h3>

<p>The chatbot uses a RAG architecture.</p>

<p>How it works:</p>

<ul>
<li>The user asks a question</li>
<li>The system searches relevant text chunks</li>
<li>The chunks are sent to the AI model</li>
<li>The model generates an answer using this context</li>
</ul>

<p>This method improves accuracy and reliability.</p>

<h3>Vector Search</h3>

<p>The project uses <b>FAISS</b> for fast similarity search.</p>

<p>FAISS allows the system to:</p>

<ul>
<li>Store document embeddings</li>
<li>Find relevant information quickly</li>
<li>Improve answer quality</li>
</ul>

<h3>Local AI Model</h3>

<p>The chatbot runs a local language model using <b>Ollama</b>.</p>

<p>Model used in this project:</p>

<ul>
<li>Llama 3.1 (8B)</li>
</ul>

<p>Running the model locally provides:</p>

<ul>
<li>Faster responses</li>
<li>Better data privacy</li>
<li>No external API needed</li>
</ul>

<h2>Technologies Used</h2>

<ul>
<li>Python</li>
<li>Sentence Transformers</li>
<li>FAISS</li>
<li>Ollama</li>
<li>RAG Architecture</li>
</ul>

<h2>Data Source</h2>

<p>The chatbot uses documentation related to MAGHREBIA home insurance, including:</p>

<ul>
<li>Insurance guarantees</li>
<li>Optional services</li>
<li>Insurance packs</li>
<li>Assistance services</li>
</ul>

<p>
The documents are converted into vector embeddings to allow semantic search.
</p>

<h2>Project Structure</h2>

<pre>
project/
│
├── assurance_complet.txt
│
├── data/
│   ├── assurance_garanties.txt
│   ├── assurance_options.txt
│   ├── assurance_packs.txt
│   └── assurance_services.txt
│
├── chunks/
│   ├── chunk files used for retrieval
│
├── chatbot_rag.py
│
└── README.md
</pre>

<h2>Example</h2>

<p><b>User question:</b></p>

<p>What does the home insurance cover?</p>

<p><b>Chatbot answer:</b></p>

<ul>
<li>Theft</li>
<li>Water damage</li>
<li>Fire and electrical damage</li>
<li>Natural events like storms</li>
</ul>

<h2>Installation</h2>

<p>Install required Python libraries:</p>

<pre>
pip install faiss-cpu sentence-transformers numpy ollama
</pre>

<p>Install the model using Ollama:</p>

<pre>
ollama pull llama3.1:8b
</pre>

<p>Run the chatbot:</p>

<pre>
python chatbot_rag.py
</pre>

<h2>Why This Project</h2>

<p>
This project demonstrates how AI can improve customer assistance in the insurance sector.
</p>

<p>It shows how to:</p>

<ul>
<li>Build a RAG chatbot</li>
<li>Process real business documents</li>
<li>Use vector search and embeddings</li>
<li>Run a local AI assistant</li>
</ul>

<h2>Author</h2>

<p><b>Fares Guesmi</b></p>

<p><b>Email</b><br>
faresguesmi815@gmail.com
</p>

<p><b>LinkedIn</b><br>
<a href="https://www.linkedin.com/in/fares-guesmi-6aa849262/">https://www.linkedin.com/in/fares-guesmi-6aa849262/</a>
</p>
