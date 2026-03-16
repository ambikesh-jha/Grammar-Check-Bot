# Grammar Check Chatbot

A Flask-based web application that provides real-time grammar checking through an interactive chat interface, powered by Llama 3.2 1B running locally via Ollama.

## Overview

This application offers a user-friendly chat interface for grammar correction. Users can input text, and the AI-powered chatbot will analyze and suggest grammar improvements. The application maintains conversation history and provides instant feedback with a modern, responsive design.

## Features

- **Real-time Grammar Checking**: Instant grammar analysis and correction suggestions
- **Interactive Chat Interface**: Clean, modern UI with user/bot message distinction
- **Conversation History**: Maintains context throughout the chat session
- **Loading Indicators**: Visual feedback during response generation
- **Local LLM Processing**: Privacy-focused with local model execution via Ollama
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Tech Stack

- **Backend**: Python Flask
- **LLM Framework**: LangChain with Ollama
- **AI Model**: Llama 3.2 1B (local)
- **Frontend**: HTML5, CSS3, JavaScript (vanilla)
- **Styling**: Custom CSS with animations

## Prerequisites

- Python 3.8+
- Ollama installed locally
- Llama 3.2 1B model pulled in Ollama

## Installation

1. Clone the repository
2. Install Ollama from [ollama.ai](https://ollama.ai)
3. Pull the Llama model:
   ```bash
   ollama pull llama3.2:1b
