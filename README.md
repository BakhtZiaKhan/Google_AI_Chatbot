# Azure AI Chatbot

A command-line AI chatbot built with Python, Microsoft Foundry, and the OpenAI Python SDK.

The application connects to a deployed AI model in Microsoft Foundry and allows users to enter prompts directly through the terminal. The chatbot continues running until the user types `quit`.

## Features

- Command-line chatbot interface
- Connects to a Microsoft Foundry model deployment
- Uses Microsoft Entra authentication through `DefaultAzureCredential`
- Loads configuration values securely from a `.env` file
- Supports both synchronous and asynchronous Python implementations
- Handles empty prompts and application errors

## Technologies Used

- Python 3.13
- Microsoft Foundry
- Azure Identity
- OpenAI Python SDK
- python-dotenv
