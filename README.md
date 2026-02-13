Retrieval-Augmented Generation (RAG) Chatbot System


Overview

This repository documents the architecture and implementation of a production-level RAG-based chatbot deployed for website live chat and WhatsApp automation.

The system prevents hallucinations by grounding LLM responses using vector-based document retrieval.


Objective

Provide accurate responses using contextual retrieval.

Capture structured lead data.

Integrate chatbot conversations into CRM.

Enable intelligent automation.


RAG Architecture

User Query
→ LLM Preprocessing
→ Embedding Generation
→ Vector Database Search
→ Context Retrieval
→ LLM Response Generation
→ CRM Storage


Engineering Contributions

Implemented RAG pipeline using embeddings + vector database.

Vectorized 200+ structured entries from Excel.

Reduced hallucinations using contextual grounding.

Built website live chatbot using OpenAI API.

Developed WhatsApp chatbot using Twilio + Meta template flow.

Stored complete conversation transcripts.

Triggered SMS notifications to sales teams.

Captured structured JSON lead data.


WhatsApp Compliance Handling

Implemented template-based conversation initiation.

Routed conversations to LLM after template handshake.

Managed Meta API policy constraints.


Tech Stack

Python
FastAPI
OpenAI
Vector Database
MongoDB
Twilio
AWS WhatsApp
