# Retrieval-Augmented Generation (RAG) Chatbot

This project implements a simple Retrieval-Augmented Generation (RAG) chatbot using a vector database for semantic search and a MySQL database for storing chat history. The chatbot is served via a Flask API.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Database Setup](#database-setup)
- [Usage](#usage)
- [Testing](#testing)
- [License](#license)

## Overview

The RAG chatbot retrieves relevant information from a text corpus based on user queries and generates responses using a language model. The chat history is stored in a MySQL database for future reference.

## Features

- Semantic search using a vector database (Chroma).
- Text embedding using the `sentence-transformers` library.
- Chat history stored in a MySQL database.
- Flask API with endpoints for chatting and retrieving chat history.

## Requirements

- Python 3.7+
- MySQL Server
- Required Python packages (listed in `requirements.txt`)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/rag-chatbot.git
   cd rag-chatbot
