# PdfChat App with Langchain and OpenAI

This is a small template that uses Langchain and OpenAI to build a PdfChat app. The app leverages OpenAI for question-answering capabilities and Langchain for text processing and retrieval.

## Features

- Extracts text from PDF documents using PyPDF2.
- Splits the text into chunks using Character Text Splitter from Langchain.
- Downloads embeddings from OpenAI to represent text.
- Creates a FAISS vector store from the text and embeddings.
- Utilizes Langchain's question-answering chain with a specified OpenAI model (e.g., text-davinci-002).
- Performs similarity search on the extracted documents.
- Allows users to ask questions about the content of PDF documents.

## Getting Started

### Prerequisites

- Python
- PyPDF2
- Langchain
- OpenAI API key
- Faiss

