# AI PDF Chatbot (RAG Application)

This project is an AI-powered PDF chatbot that allows users to upload a PDF document and ask questions about its content.

The system uses Retrieval-Augmented Generation (RAG) to search the document and return relevant answers.

## Features

* Upload any PDF document
* Ask questions related to the document
* AI retrieves relevant text from the document
* Chat history support
* Clean UI using Streamlit

## Tech Stack

* Python
* LangChain
* FAISS (Vector Database)
* HuggingFace Embeddings
* Streamlit

## Project Architecture

PDF Upload
↓
Text Extraction
↓
Text Chunking
↓
Embeddings (HuggingFace)
↓
Vector Search (FAISS)
↓
Answer Retrieval

## Installation

Clone the repository:

git clone https://github.com/Azhar-2002/llm-pdf-chatbot.git

Navigate to the project folder:

cd llm-pdf-chatbot

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py

## Example Questions

What is Artificial Intelligence?

What industries are impacted by AI?

What are common applications of AI?

## Future Improvements

* Support multiple PDFs
* Add LLM-based answer generation
* Deploy using Streamlit Cloud
* Improve UI with chat interface
## Live Demo

Try the application here:

https://llm-pdf-chatbot-fdbvzf2rpuwnr7xxplx59z.streamlit.app/

## Author

Md Azhar Ansari
