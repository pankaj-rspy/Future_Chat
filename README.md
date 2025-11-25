# FUTURE_CHAT
A Local LLM-Based Multi-Modal Conversational AI System

FUTURE_CHAT is a fully offline conversational AI system built using Python, Ollama, and local LLM models such as LLaMA, Mistral, and Phi. It includes:

- Local LLM inference (fully offline)
- Persistent memory
- Chat history storage
- Text-to-speech (TTS) output
- Model switching
- Simple frontend interface

This project was created as part of an M.Tech project.

------------------------------------------------------------

## Features

1. Local LLM Engine (Ollama)
   - Runs quantized local models
   - No internet required

2. Memory Module
   - Stores important user information
   - Persists across runs

3. Chat History
   - Saves all messages to the "history" folder

4. Text-to-Speech (TTS)
   - Generates spoken audio responses locally

5. Custom Frontend
   - Built using HTML, CSS, JavaScript

------------------------------------------------------------

## Project Structure

FUTURE_CHAT/
│-- main.py
│-- llama_client.py
│-- ollama_client.py
│-- memory.py
│-- tts.py
│-- requirements.txt
│
├── frontend/
│   ├── index.html
│   ├── script.js
│   └── styles.css
│
├── history/
│   └── saved conversations
│
└── README.md

------------------------------------------------------------

## Installation and Setup

1. Install dependencies:
   pip install -r requirements.txt

2. Install Ollama from:
   https://ollama.ai

3. Pull a model:
   ollama pull llama3

4. Run the backend:
   python main.py

5. Open the frontend:
   Open the file: frontend/index.html in any browser

------------------------------------------------------------

## How It Works

- Frontend sends user messages to backend
- Backend sends prompt to local Ollama model
- Model generates response
- Memory is updated
- Optional TTS audio is generated
- Frontend displays message and audio

------------------------------------------------------------

## Results

- Typical model response: 1.5 to 3 seconds
- Fully offline system
- Smooth performance on mid-range hardware

------------------------------------------------------------

## Contributor


Pankaj Kumar
Tushar Bhardwaj

------------------------------------------------------------

## Support

If you found this useful, consider giving the repo a star.
