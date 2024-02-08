# ChatPDF: A Conversational Interface for arXiv Papers

## Project Overview
ChatPDF leverages advanced AI technologies to create a conversational interface that interacts with research papers from arXiv, providing users with an intuitive way to explore and understand complex scientific documents. Using a sophisticated Retriever-Reader-Generator (RAG) pipeline, the application ingests PDF documents, extracts text, and enables real-time chat functionalities to discuss the papers' content.

## Key Components
- **LangChain**: Utilizes LangChain for document processing and embedding.
- **Chroma Vector Store**: Employs Chroma for efficient document retrieval based on semantic similarity.
- **Ollama**: Leverages Ollama for generating conversational responses.
- **Sentence Transformers & FastEmbed Embeddings**: Integrates advanced embedding techniques for accurate context understanding.

## Installation

### Prerequisites
- Python 3.8+
- Pip

### Setup Environment
```bash
python -m venv chatpdf-env
source chatpdf-env/bin/activate  # On Windows use `chatpdf-env\Scripts\activate`
