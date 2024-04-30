# ollama-local-rag

## Overview
This script demonstrates how to use LangChain, a library for natural language processing tasks. It utilizes various components such as document loaders, vector stores, embeddings, language models, and callback handlers.

## Components

### Document Loaders
- `PyPDFLoader`: Loads PDF documents for processing.

### Vector Stores
- `Chroma`: Provides functionality for creating vector representations of documents.

### Embeddings
- `GPT4AllEmbeddings`: Embedding model for generating contextualized representations of text.

### LangChain
- `PromptTemplate`: Template for generating prompts for question answering tasks.
- `Ollama`: Language model for text generation tasks.

### Callbacks
- `CallbackManager`: Manages callback functions for handling output streams.
- `StreamingStdOutCallbackHandler`: Handles streaming output to stdout.

### Chains
- `RetrievalQA`: Implements a question answering system using retrieval-based methods.

## Usage
- Ensure all required libraries are installed.
- Modify the `pdf_files` list to include the paths of PDF files for processing.
- Run the script.
- Input queries when prompted. Type 'exit' to quit.