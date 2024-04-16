# LAWGPT 📄

A Generative AI-powered Question and Answer app that responds to questions about your PDF files using LangChain and Hugging Face pipelines.

## Features

- Answers questions about your PDF files using Generative AI.
- Utilizes LangChain for natural language processing.
- Uses Hugging Face's pipelines for text generation.
- Retrieves contextual information from PDFs and provides accurate answers.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/PrathameshBRaut/lawgpt.git
    ```

2. Change to the project directory:

    ```bash
    cd lawgpt
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Requirements

- Python 3.10 or later
- Libraries: [torch, transformers, langchain, chromadb, pypdf, auto_gptq, pdf2image, sentence_transformers, InstructorEmbedding, xformers, fastapi, uvicorn, pydantic, requests, pyngrok, nest-asyncio, streamlit]

## How It Works

- The application uses a Llama-2-13B chat model for causal language modeling.
- PDF documents are loaded using LangChain's document loaders.
- Embeddings are created using the InstructorEmbedding model from `hkunlp/instructor-large`.
- The application utilizes `pyngrok` for creating a public URL for the API, which can be accessed externally.
