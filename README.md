# Gradio Chatbot Application

## Overview

This is a simple chatbot application using Gradio and Google's GenerativeAI API. The chatbot leverages the Gemini Pro model from GenerativeAI to provide interactive conversations.

## Features

- Interactive chat interface powered by Gradio.
- Integration with Google's GenerativeAI for natural language processing.
- Clear button for resetting the chat history.

## Getting Started

### Prerequisites

- Python 3.10 
- Gradio
- Google's GenerativeAI API Key

### Installation

1. Install the required packages from requirements.txt file

2. Obtain an API key from [Google's GenerativeAI](https://makersuite.google.com/app/apikey).

3. Configure the API key in your application:

    ```python
    genai.configure(api_key="Your_GenerativeAI_API_Key")
    ```

## Usage

1. Run the application:

    ```bash
    python app.py
    ```

2. Open the provided Gradio interface in your web browser.

3. Enter a message in the "User" textbox and click the "Chat" button to interact with the chatbot.

4. Use the "Clear" button to reset the chat history.

## Configuration

- Configure the GenerativeAI API key in your application as mentioned in the installation steps.




