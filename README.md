# Smart AI Prompt Engineer – LLM Chatbot

An AI-powered chatbot built using Groq LLM and Python, focused on prompt engineering, role-based behavior, and conversation memory.

The project demonstrates how structured prompts and memory can be used to guide LLM responses effectively for beginner-friendly explanations.

## Project Overview

This project showcases a Smart AI Prompt Engineer chatbot that:

-Uses system-level prompting to control AI behavior

-Maintains conversation memory across interactions

-Supports both terminal-based and Gradio web UI interfaces

-Focuses on clear, beginner-friendly explanations

-The chatbot is designed to act like a helpful AI tutor, explaining concepts in simple language with examples.

## Features

1.Role-based Prompting

-Uses a system prompt to define AI personality and behavior

2.Conversation Memory

-Maintains multi-turn context during a session

3.Groq LLM Integration

-Uses llama-3.1-8b-instant model

4.Two Interfaces

-Terminal chatbot (commented for reference)

-Gradio-based web interface

5.Configurable Creativity

-Supports temperature control for response variation

## Prompt Engineering Highlights

The chatbot behavior is controlled using a system prompt:

-You are a Smart AI Prompt Engineer.

-Your job is to help beginners learn concepts clearly.

-Explain in simple words.

-Use examples when needed.

-Be friendly and encouraging.


This ensures:

-Clear explanations

-Beginner-focused responses

-Consistent tone and style

-Reduced hallucinations

## Project Structure

smart-ai-prompt-engineer-chatbot/

├── chatbot.py        # Core LLM logic, prompts, and memory handling

├── gradio_app.py     # Gradio-based web interface

├── __pycache__/      # Python cache files

└── README.md

## Tech Stack

-Language: Python

-LLM Provider: Groq

-Model: llama-3.1-8b-instant

-UI Framework: Gradio

-Environment: VS Code

## API Key Setup

This project uses environment variables for security.

Windows (PowerShell)

setx GROQ_API_KEY "your_api_key_here"

## How to Run the Project

1️. Install dependencies

pip install groq gradio

2️. Run the Gradio app

python gradio_app.py

3️. Open in browser

Gradio will provide a local URL (e.g.):

http://127.0.0.1:7860

## User Interface

Text-based input field for user questions

AI-generated response displayed in output box

Clear button to reset input

Simple and clean UI focused on functionality

Note: This version is not chat-bubble based. Each question is handled independently, while memory is maintained internally during the session.

## Author

Suchithra B

AI / LLM Engineering Intern Aspirant

Focused on Prompt Engineering, LLM applications, and real-world AI systems

