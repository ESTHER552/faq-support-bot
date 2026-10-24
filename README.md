# FAQ Support Bot - n8n AI Agent

An AI-powered FAQ support bot built with n8n, Google Gemini, and a retrieval-based FAQ search tool. The workflow is designed to answer common customer questions and provide a route for escalating issues to a human when needed.

## Project Overview

The goal of this project is to explore how AI agents can support customer service by retrieving relevant FAQ information, generating helpful responses, and allowing more complex issues to be escalated.

## Workflow Architecture

The workflow includes:

- **Chat Trigger:** Receives incoming messages from users.
- **AI Agent:** Processes questions and coordinates the response.
- **Google Gemini Chat Model:** Powers the agent's language understanding and response generation.
- **FAQ Search Tool:** Retrieves relevant information from the FAQ knowledge source.
- **Google Gemini Embeddings:** Converts text into vector representations to support semantic search.
- **Human Escalation:** Includes a Gmail-based escalation tool for situations that require human support.

## Technologies Used

- n8n - workflow automation and AI agent orchestration
- Google Gemini - language model and embeddings
- FAQ search / vector retrieval - knowledge-grounded responses
- Gmail - human escalation

## Key Features

- Conversational FAQ support
- Retrieval-based information lookup
- AI-generated responses grounded in FAQ content
- Human escalation workflow
- Modular workflow design

## Workflow Screenshot

<img width="1402" height="847" alt="FAG Support Bot" src="https://github.com/user-attachments/assets/b384ccdf-06cc-473c-9815-112edd8b4e5e" />


## How It Works

1. A user sends a message through the chat trigger.
2. The AI agent interprets the question.
3. The FAQ search tool retrieves relevant knowledge.
4. The agent uses the retrieved information to formulate a response.
5. If human assistance is needed, the escalation tool provides a route to notify the support team.
