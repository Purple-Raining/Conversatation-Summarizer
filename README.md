# Conversation Summarizer & JSON Extraction

**Author:** Omkar Patil  
**Date:** 2025-09-17

## Project Overview
This repository contains a Google Colab notebook demonstrating two tasks:

1. **Task 1: Managing Conversation History with Summarization**
    - Maintains a running conversation history of user–assistant chats.
    - Implements summarization logic to keep conversation concise.
    - Supports truncation by number of conversation turns, character count, or word count.
    - Periodically summarizes the conversation every k-th run.
    - Demonstrates feeding multiple conversation samples and shows truncation outputs.

2. **Task 2: JSON Schema Classification & Information Extraction**
    - Extracts structured information (name, email, phone, location, age) from chats.
    - Uses Groq/OpenAI-compatible API for structured extraction.
    - Includes a safe regex fallback for offline extraction.
    - Demonstrates parsing of at least 3 sample chats with validation against the JSON schema.

## Features
- Fully implemented in **Python** without external frameworks.
- API integration with **Groq/OpenAI-compatible client**.
- Clean, well-documented code and visible outputs for each task.
- Versioned using **GitHub** for easy tracking and evaluation.

## Requirements
- Python 3.8+  
- Standard libraries: `os`, `json`, `re`, `getpass`  
- Groq/OpenAI-compatible API key for structured extraction (optional fallback to regex if unavailable)

## How to Run
1. Open the notebook in Colab.
2. Run each cell in order.
3. For Task 2, input your **Groq API key** when prompted using `getpass()` to securely set it.
4. Review outputs in the demonstration sections.

## License
This repository is for educational purposes and assignment submission.  

**Repository Links:**

- **Google Colab Notebook:** [Open in Colab](https://colab.research.google.com/github/YourUsername/conversation-summarizer/blob/main/Task1_Conversation_Summarizer.ipynb)  
- **GitHub Repository:** [View on GitHub](https://github.com/YourUsername/conversation-summarizer)
