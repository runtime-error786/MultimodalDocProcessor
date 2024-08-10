# Multimodal PDF Content Extractor and Summarizer

This project provides a comprehensive tool for extracting and summarizing content from PDF documents. It supports text, tables, and images, using advanced language models and embeddings for content analysis and similarity search.

## Features

- **PDF Extraction**: Extracts text, tables (future implementation), and images from PDF files.
- **Text Summarization**: Splits and summarizes large text chunks using an LLM.
- **Image Summarization**: Summarizes image content using a language model.
- **FAISS Integration**: Uses FAISS for efficient similarity search on text, table, and image embeddings.
- **Query System**: Allows querying across different content types to retrieve relevant information and descriptions.
- **Image Display**: Displays relevant images extracted from the PDF.

## Installation

To run this project, ensure you have Python 3.11.3 installed. Then, install the required packages using pip:

```bash
pip install numpy faiss-cpu pymupdf pillow langchain langchain_community
