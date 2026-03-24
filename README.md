# Chat with PDF - RAG Pipeline
A Retrieval-Augmented Generation (RAG) application that allows users to have context-aware conversations with PDF documents.

## 🚀 Features
* **PDF Parsing:** Efficient text extraction from multi-page documents.
* **Vector Embeddings:** Uses OpenAI/HuggingFace embeddings for semantic search.
* **Vector Store:** Integrated with Pinecone for high-speed retrieval.
* **Smart Chunking:** Implemented RecursiveCharacterTextSplitter to maintain context and handle token limits.

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** LangChain
* **Database:** Pinecone (Vector DB)
* **LLM:** OpenAI GPT-3.5/4

## 🔧 Technical Challenge Overcome
During development, I faced issues with API rate limits and long document context windows. I solved this by implementing an asynchronous chunking strategy and a retry-logic mechanism, reducing failed queries by 40%.
