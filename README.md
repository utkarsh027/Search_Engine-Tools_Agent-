# README: LangChain Streamlit App with Search Capabilities

## Overview

This project is a Streamlit application that integrates LangChain and Groq for building an intelligent chatbot. The chatbot can search the web, access academic papers via Arxiv, and retrieve information from Wikipedia. It provides an interactive user interface to communicate with the AI, view its thought process, and display the results of its actions.

## Features

- **Web Search**: The chatbot can perform real-time web searches using DuckDuckGo.
- **Academic Search**: Retrieve academic papers via Arxiv API.
- **Wikipedia Search**: Fetch concise information from Wikipedia.
- **Interactive UI**: Built with Streamlit for easy interaction.
- **Thought Display**: Visualize the reasoning process of the AI.

# Requirements

The application requires Python 3.8 or higher and the following dependencies, which are listed in the `requirements.txt` file:


# Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/utkarsh027/Search_Engine-Tools_Agent-.git

#Create a Virtual Environment:
```bash
python -m venv venv
source venv/bin/activate venv
```

#Install Dependencies:
```bash
pip install -r requirements.txt
```

#Set Up Environment Variables: 

Create a .env file in the root directory with your Groq API key:

GROQ_API_KEY=your_groq_api_key

#Run the Application:
```bash
python -m streamlit run app.py
```

#Interact with the Chatbot:

Enter your Groq API key in the sidebar.
Ask questions in the chat input box, such as "What is machine learning?".
View responses and the chatbot's reasoning process.


