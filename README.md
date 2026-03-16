# Pin-AI-IT-Support-Chatbot

AI-powered IT support chatbot using Retrieval-Augmented Generation (RAG) to answer technical questions from internal enterprise documentation and create service desk tickets when issues cannot be resolved.

## Overview

Pin was developed as part of a University of Washington Tacoma senior capstone project. The system assists users with troubleshooting common IT issues by retrieving relevant documentation and generating contextual AI responses.

If the issue cannot be resolved through automated assistance, the system escalates the request by generating a service desk ticket.

## Key Features

- AI-powered IT troubleshooting assistant
- Retrieval-Augmented Generation (RAG) for contextual responses
- Semantic search over internal IT documentation
- Automated service desk ticket creation
- Modular backend architecture

## Technology Stack

- Python
- FastAPI
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Git / GitHub

## System Architecture

The system uses a Retrieval-Augmented Generation pipeline:

1. User submits a question through the chatbot interface  
2. The system retrieves relevant documentation from the knowledge base  
3. The retrieved context is passed to the language model  
4. The model generates a troubleshooting response  
5. If unresolved, a service desk ticket is created

## Team

Developed collaboratively by a team of five students as part of the UW Tacoma IT Senior Capstone project.
