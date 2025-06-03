# chat-bot-web-app

# LLM Chatbot Web Application

A chatbot is a computer program that takes a text input, and returns a corresponding text output.

Chatbots use a special kind of computer program called a transformer, which is like its brain. Inside this brain, there is something called a language model (LLM), which helps the chatbot understand and generate human-like responses. It deciphers many examples of human conversations it has seen prior to responding in a sensible manner.

This project is a simple web-based chatbot application using a pre-trained language model from Hugging Face and a Flask backend. It integrates a chatbot interface with a backend API to demonstrate how to communicate between frontend and server using HTTP requests.

## 🚀 Features

- Web-based chatbot interface
- Flask-powered backend
- Integration with Hugging Face's BlenderBot (`facebook/blenderbot-400M-distill`)
- JavaScript-based frontend to send and receive chat messages
- Support for ongoing conversation history

## 📁 Project Structure

│
├── app.py # Flask backend application

├── requirements.txt # Required Python packages

├── static/

│ 

└── script.js # Handles chat interaction with the backend

└── templates/

└── index.html # Chatbot interface

## 🔧 Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/kalelei/chat-bot-web-app.git

2. **Install packages**:
   python3.11 -m pip install -r LLM_application_chatbot/requirements.txt


## ▶️ Runnin The App
cd LLM_application_chatbot/

flask run
