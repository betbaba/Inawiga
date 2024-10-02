# Inawiga: Retrieval-Augmented Generation (RAG) with Llama3 on Groq

Welcome to **Inawiga**, a Retrieval-Augmented Generation (RAG) system that leverages **Llama3** models on Groq for generating responses based on retrieved documents or website content. This project demonstrates the integration of Llama3 with embeddings from Ollama, using **PgVector** for vector storage and retrieval, and **Streamlit** for the web interface.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Using the App](#using-the-app)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)

## Features

- Upload PDFs or provide URLs for content retrieval.
- Use Ollama for text embeddings (OpenAI can also be used).
- Ask questions based on the content in real-time.
- Integrated with PgVector for efficient vector storage.
- Powered by Llama3 on Groq for generating high-quality, context-aware responses.
- Easy-to-use Streamlit interface for interacting with the system.

## Installation

### Prerequisites

- Python 3.8+
- Docker Desktop
- Groq API Key (for using Llama3)
- Ollama installed for embeddings

## Using the App

- **Add a PDF or URL:** You can upload a PDF file or input a URL to extract content.
- **Ask questions:** After the content is processed, you can interact with it by asking questions, and the RAG system will generate responses based on the embedded information.

### Example Questions:
- What did Meta release in 2024?
- Tell me more about the Llama3 models.

## Tech Stack

- **Llama3 on Groq:** For generating high-quality responses.
- **Ollama:** For creating text embeddings used in content retrieval.
- **PgVector:** PostgreSQL extension for storing and retrieving vectors efficiently.
- **Streamlit:** For creating a web-based interface to interact with the RAG system.
- **Docker:** For managing PgVector as a containerized service.

## Project Structure

```plaintext
Inawiga/
├── app.py               # Main Streamlit application
├── requirements.txt     # Python dependencies
├── .run_pgvector.sh     # Helper script to run PgVector
├── README.md            # Project documentation (this file)
└── other source files
```
