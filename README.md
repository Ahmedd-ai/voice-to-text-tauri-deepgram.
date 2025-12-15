# Voice-to-Text Tauri Deepgram

A desktop voice-to-text application built using **Tauri** and **JavaScript**.

The application records audio from the microphone and converts speech into
text using the **Deepgram Speech-to-Text API**.

## Features
- Record audio using microphone
- Convert voice to text
- Desktop application using Tauri
- Secure API key handling (no key stored in repository)

## Tech Stack
- Tauri
- JavaScript
- Rust (Tauri backend)
- Deepgram Speech-to-Text API

## Setup Instructions

1. Clone the repository
```bash
git clone https://github.com/Ahmedd-ai/voice-to-text-tauri-deepgram.git
cd voice-to-text-tauri-deepgram

Install dependencies
npm install


Add your Deepgram API key
Create a .env file inside src-tauri:
DEEPGRAM_API_KEY=your_deepgram_api_key_here

Run the application
npm run tauri dev
