Constitution RAG - Notebook Project
A cutting-edge Retrieval-Augmented Generation (RAG) project designed to interact with and query constitutional data using LangChain, ChromaDB, Google Search, and interactive terminal agents. This project empowers users to explore constitutional documents through natural language queries, leveraging advanced embeddings and conversational AI.
🌟 Features

Knowledge Base Management: Load and manage constitutional data using ChromaDB for efficient storage and retrieval.
Conversational Querying: Query constitutional data with interactive, conversational agents powered by LangChain.
Embedding & Retrieval: Utilize state-of-the-art embedding models for accurate retrieval-based question answering.
Google Search Integration: Augment queries with real-time web search capabilities for enhanced context.
Interactive Terminal: Engage with the system via a user-friendly terminal interface for seamless interaction.

📂 Contents

Data Loading: Import and process constitutional documents into a structured knowledge base.
ChromaDB Integration: Store and index document embeddings for fast retrieval.
LangChain Agents: Build conversational agents with tool integrations for dynamic querying.
Embedding-Based Q&A: Retrieve relevant constitutional excerpts and generate precise answers.
Google Search Tool: Enhance responses with external web data when needed.

🛠️ Installation
Prerequisites

Python 3.11
Git
A valid API key for LangChain-compatible models (e.g., xAI's Grok API)
Optional: Google Search API key for web search functionality

Steps

Install Dependencies:
pip install -r requirements.txt


Set Up Environment Variables:

Create a .env file in the project root.
Add your API keys (e.g., for xAI's Grok API or Google Search API):XAI_API_KEY=your_xai_api_key
GOOGLE_API_KEY=your_google_api_key




Run the Notebook:

Open the Jupyter Notebook:jupyter notebook constitution_rag.ipynb


Follow the notebook instructions to load data, initialize agents, and start querying.



🚀 Usage

Load Constitutional Data:

Place your constitutional document (e.g., a PDF or text file) in the data/ directory.
Run the notebook cells to process and embed the data into ChromaDB.


Query the System:

Use the interactive terminal or notebook interface to ask questions like:
"What are the fundamental rights in the constitution?"
"Explain the amendment process."


The system retrieves relevant document chunks and generates answers using LangChain and Grok.


Web-Augmented Queries:

For queries requiring external context, the Google Search tool fetches real-time information to supplement the response.



📚 Dependencies

LangChain: Framework for building RAG and conversational agents.
ChromaDB: Vector database for storing and retrieving document embeddings.
PyPDF2: For extracting text from PDF documents.
python-dotenv: For managing environment variables.
Google Search API: For web-based context augmentation.
Jupyter: For running the interactive notebook.
Additional dependencies are listed in requirements.txt.

🔧 Configuration

ChromaDB: Configure the database path in the notebook (default: ./chroma_db).
API Keys: Ensure API keys are correctly set in the .env file.
Embedding Model: Uses LangChain-compatible embedding models (e.g., Hugging Face or xAI embeddings).
Language Model: Integrates with xAI's Grok for response generation (API key required).

🌐 Example Queries

"What is Article 21 of the constitution?"
"How does the constitution define citizenship?"
"Search for recent amendments to the constitution."

🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch: git checkout -b feature-name
Commit your changes: git commit -m "Add feature-name"
Push to the branch: git push origin feature-name
Submit a pull request.


🙏 Acknowledgments

LangChain for the RAG framework.
ChromaDB for efficient vector storage.
Google Search API for real-time web augmentation.

