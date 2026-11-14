
# AI Document Intelligence

An AI-powered document assistant that allows users to upload PDF documents and ask questions in natural language. It retrieves relevant information from uploaded documents and generates context-based answers using Retrieval-Augmented Generation (RAG).

## Project Overview

AI Document Intelligence helps users quickly understand long documents without manually searching through every page.

Users can upload a PDF, ask questions, and receive relevant answers or a structured summary based on the document content.

## Key Features

- PDF document upload
- Automatic document processing and indexing
- AI-powered question answering
- Document summarization
- Context-based information retrieval
- Answers grounded in uploaded document content
- User authentication and document access control

## Technology Stack

- n8n – Workflow automation
- OpenAI – AI language model and embeddings
- Supabase – Authentication and backend services
- Qdrant – Vector database for document retrieval
- HTML, CSS and JavaScript – Frontend
- GitHub Pages – Frontend hosting

## How It Works

1. User logs into the application.
2. User uploads a PDF document.
3. The document is processed and indexed.
4. User submits a question about the document.
5. The AI workflow retrieves relevant information from Qdrant.
6. OpenAI generates an answer based on the retrieved content.
7. The answer is displayed in the application.

## n8n Workflows

### Workflow 13 – PDF Upload & Indexing

- Receives uploaded PDF documents.
- Processes document content.
- Generates embeddings.
- Stores document vectors in Qdrant.

### Workflow 14 – AI Document Question Answering

- Receives user questions.
- Searches relevant document content in Qdrant.
- Uses an AI Agent to generate context-based answers.
- Returns the answer to the application.

## Example Use Cases

- Summarizing company handbooks
- Finding employee policies
- Retrieving office timings and working days
- Extracting project information
- Answering questions from business documents

## Project Demo

Live Application: https://bijaya-automates.github.io/ai-document-intelligence/

## Project Status

Core application and both n8n workflows have been implemented and tested.

---

Built with OpenAI, n8n, Supabase and Qdrant.

## Project Demo Video

Watch the recorded demonstration of the AI Document Intelligence workflow.

[Watch Demo Video](AI-Document-Intelligence-Demo-Compressed.mp4)

The demo covers:
- PDF document upload
- Asking questions about the uploaded document
- Receiving AI-generated answers using RAG
