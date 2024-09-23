# LangChain FAISS VectorStore with LLAMA 3.1

This project demonstrates how to use **LangChain** with **LLAMA 3.1** embeddings and a **FAISS VectorStore** to create a retrieval-augmented system for similarity search. The system enables efficient document retrieval based on vector embeddings.

## Features

- **LLAMA 3.1 Embeddings**: Uses LLAMA 3.1 embeddings through the `OllamaEmbeddings` class.
- **FAISS Vector Store**: Stores document vectors and allows efficient similarity searches.
- **Similarity Search**: Given a query, the system retrieves the most similar document from the vector store.

## Requirements

The following libraries are required to run the notebook:

- Python 3.8+
- [LangChain](https://github.com/hwchase17/langchain)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Ollama](https://github.com/ollama)
