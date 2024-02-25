# RAG-PDF-Chat Application

## Description

The **RAG-PDF-Chat** application is a versatile tool designed to facilitate interactive and insightful conversations with PDF documents. Leveraging the power of LangChain and Hugging Face models, this application allows users to engage in chat-based queries and obtain relevant information from PDF files seamlessly.

### Key Features

- **Chat Interface**: A user-friendly chat interface for interacting with PDF documents.
- **RAG Integration**: Utilizes the RAG (Retrieval-Augmented Generation) model for enhanced document understanding.
- **PDF Parsing**: Extracts and analyzes information from PDF files for effective communication.
- **LangChain and Hugging Face Models**: Leverages state-of-the-art language models to provide accurate and context-aware responses.

## User Instructions

### Setup

1. Clone the repository: `git clone https://github.com/Bansal2905/RAG-Chat-with-PDF-.git`
2. Install dependencies: `pip install -r requirements.txt`

### Usage

1. Run the application: `python app.py`
2. Access the application through your web browser at `http://localhost:5000`.
3. Upload a PDF document using the provided interface.
4. Engage in a chat conversation by typing queries and receiving responses.

### Example Interaction

```plaintext
User: What is the publication date of the document?
RAG-PDF-Chat: The publication date of the document is [date].

User: Summarize the key findings.
RAG-PDF-Chat: Here are the key findings of the document: [summary].

User: Search for information on [specific topic].
RAG-PDF-Chat: I found relevant information on [specific topic] in the document. [details].
