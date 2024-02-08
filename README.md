# Medical-Chatbot-using-RAG

This repository contains code for a Medical Chatbot built using RAG (Retrieval-Augmented Generation). The chatbot is designed to assist users with medical queries, providing responses sourced from reliable medical databases and websites.

## Features
1. **Voice Input**: Users can interact with the chatbot using voice queries, which are transcribed into text for processing.
2. **RAG Model**: Utilizes RAG for generating responses based on retrieved context.
3. **Google Search API Integration**: Retrieves relevant context from the web using Google Search API. Also provides sources for the retrieved information.

## Setup
To set up the Medical Chatbot, follow these steps:

1. **Obtain Google Search API Credentials**: Get your `GOOGLE_CSE_ID` and `GOOGLE_API_KEY` to use the Google Search API for retrieving context.
2. **Get OpenAI API Key**: Obtain an API Key for the OpenAI GPT-3.5-Turbo model for generating responses.
3. **Create Pinecone Vector Database**: Create a Vector Database using your data to enable efficient retrieval of information.
4. **Access the Chatbot UI**: Access the chatbot interface through your web browser.

## Dependencies
- Python 3.x
- Pinecone
- Google Search API
- OpenAI API
- Gradio
- Langchain

## Usage
1. Input your medical query via voice or text.
2. The model will transcribe voice input (if applicable) and process the query.
3. It will then retrieve relevant information using the RAG over Vector DB or using the Google Search API.
4. Sources for the retrieved information will be provided for reference.
5. We have also implemented a chatbot based on text input.
6. We have used Gradio tab interfaces to compare various approaches.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your proposed changes.


Thank you for using our Medical Chatbot! We hope it proves helpful for your medical inquiries.
