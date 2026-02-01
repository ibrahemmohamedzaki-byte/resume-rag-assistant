# resume-rag-assistant

RAG Resume Chatbot
A simple Retrieval-Augmented Generation (RAG) project that allows chatting with a resume or PDF documents instead of manually searching through them.
The goal was to build an automated pipeline that processes documents and lets the user ask questions based on real data.
How It Works
Upload a PDF file (e.g., a resume) to Google Drive
The workflow automatically downloads the file
Extracts text from the PDF
Splits the text into smaller chunks
Converts the chunks into embeddings
Stores them in a Supabase Vector Database
An AI Agent retrieves the most relevant information and answers based on the document content
Features
Chat with Resume / PDF
Automated Document Ingestion Pipeline
Vector Search using Supabase
AI Agent with Memory
Reduced Hallucinations
Continuous Conversation Context
No-Code / Low-Code Workflow Automation
Tech Stack
n8n (Workflow Automation) 
Supabase Vector Store
HuggingFace Embeddings
RAG Architecture
AI Agent + Memory
Google Drive Integration
Example Questions
What skills do I have?
Which projects did I work on?
What is my education background?


What skills do I have?
Which projects did I work on?
What is my education background?
