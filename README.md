# Retrieval-Augmented Generation (RAG) Pipeline with LangChain, ChromaDB, and OpenAI APIs

## Overview

This project implements a small Retrieval-Augmented Generation (RAG) pipeline using LangChain, ChromaDB, and OpenAI APIs. The RAG approach combines information retrieval with generative AI models, enabling the system to answer queries with both up-to-date and accurate contextual information. This repository showcases how to build such a pipeline efficiently using Python.

## Features

- **LangChain Integration:** Leveraging the power of LangChain for seamless interaction with language models.
- **ChromaDB for Vector Storage:** Efficient document embeddings and retrieval using ChromaDB, a high-performance vector database.
- **OpenAI API Integration:** Utilizes OpenAI's GPT models for text generation based on retrieved documents.
- **Scalable Pipeline:** Easily extendable and scalable for larger datasets or more complex use cases.

## Tech Stack

- **Python 3.x**
- **LangChain**
- **ChromaDB**
- **OpenAI GPT Models**
- **Faiss (optional, for fast similarity search)**

## Getting Started

### Prerequisites

Before setting up the project, ensure you have the following installed:
    ```
    pip install requirements.txt
    ```

- Python 3.12
- A valid OpenAI API key (set up .env file)
- ChromaDB installed


### Usage

**Query the Pipeline:**
   Put the file you want to query in the 'docs' folder and run the RAG pipeline using:
    ```
    python multi-doc.py
    ```
