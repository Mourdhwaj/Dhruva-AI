# Dhruva AI Assistant

Dhruva AI Assistant is a Streamlit application that allows users to upload documents, generate embeddings, store vector databases, and chat with an AI assistant. 
This project leverages multiple AI models and libraries to create an interactive and intelligent assistant.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
  

## Installation

To get started with this project, you need to set up the required environment and dependencies.

**Create and activate a virtual environment:**
python -m venv venv
.\venv\Scripts\activate  # On Windows
source venv/bin/activate  # On macOS/Linux

**Install the required packages:**
pip install -r requirements.txt


**Set up environment variables: Create a .env file in the project directory and add your API keys:**
GROQ_API_KEY=your_groq_api_key
NVIDIA_API_KEY=your_nvidia_api_key

**Run the application:**
streamlit run main.py
