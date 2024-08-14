# Multidoc VectorStore
FAISS, LangChain, Mesop, HuggingFaceEmbeddings

## Description
Multidoc VectorStore is an advanced document retrieval system designed to handle multidocument storage and retrieval efficiently. This project leverages the power of FAISS for vector-based similarity search, integrates various document loaders and splitters using LangChain, and uses HuggingFace embeddings for accurate vector representations of documents. With a user-friendly interface built using Mesop, this system provides seamless interaction for retrieving documents, answering queries, and exploring large-scale document collections.

## Features
Efficient Document Retrieval: Uses FAISS for fast and accurate vector-based document retrieval.
Multidocument Support: Handles various file types such as PDFs, TXT, and CSV, and manages large documents with custom text splitters.
Embeddings Integration: Utilizes HuggingFace embeddings to enhance query accuracy and relevance.
Custom Retrievers: Implements custom retrievers like BM25, Ensemble, and LongContextReorder to optimize search relevance.
Branches
main: The primary branch containing the fully integrated multidocument vector store with FAISS and HuggingFace embeddings.
retriever-optimization: This branch includes work on optimizing retrievers for better search relevance and performance.

## Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/MultidocVectorStore.git
Install the required dependencies using pip:
bash
Copy code
pip install -r requirements.txt
Set up your environment variables (if applicable) to configure paths, model names, and other settings.

## Usage
Run the vector store system with the following command:
bash
Copy code
python run_vectorstore.py
Document Ingestion
Add new documents by placing them in the specified folder for ingestion.
The system will automatically process, embed, and store them in the FAISS index.
Query and Retrieval
Use the Mesop interface to search for relevant documents, ask questions, and explore the stored content.
Customization
Modify the configuration file (config.json) to adjust settings like embedding model, chunk size, text splitter method, and retriever choices.
Add new retrievers or modify existing ones to suit your specific use case.

## Contributing
Fork the repository.
Create a new branch for your feature or bug fix:
bash
Copy code
git checkout -b feature-new-functionality
Commit your changes and open a pull request.

## Acknowledgments
LangChain for providing the framework to build document loaders and text splitters.
HuggingFace for embedding models that power our vector search.
FAISS for efficient vector-based similarity search.
Mesop for enabling an interactive and user-friendly interface.
