# Local Low-Code Chatbot with Ollama and Flowise

Create a fully functional, local chatbot using [Flowise](https://flowiseai.com/) and [Ollama](https://ollama.com/). This project is designed to provide a low-code, privacy-friendly solution for building intelligent conversational bots. 🚀

## Features
- **Low-Code Workflow:** Build chatbots visually without heavy coding.
- **Local Hosting:** Keeps your data private and secure.
- **Customizable:** Fully adjustable to your needs.
- **Powered by Open-Source Models:** Utilizes Ollama's LLMs for AI capabilities.

## Workflow Overview
![Workflow Diagram](./assets/chatbot_workflow.png)

### Core Components
1. **ChatOllama:** Provides AI responses using Ollama's models.
2. **Buffer Memory:** Retains chat history for continuity.
3. **Conversation Chain:** Integrates ChatOllama and Buffer Memory to enable interactive conversations.

## Getting Started

### Prerequisites
- [Docker](https://www.docker.com/) (for running Ollama locally)
- [Node.js](https://nodejs.org/) and npm (for Flowise)
- A compatible LLM model (e.g., `SARA-llama3.2`)

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/dwain-barnes/local-low-code-chatbot-ollama-flowise.git
    cd local-low-code-chatbot-ollama-flowise
    ```
2. Start Ollama:
    ```bash
    docker run -p 11434:11434 ollama/server
    ```
3. Install Flowise:
    ```bash
    npm install -g flowise
    flowise start
    ```
4. Import the provided Flowise JSON (`basic-local-chatbot-flowise.json`) into Flowise.

### Running the Chatbot
1. Access the Flowise editor at `http://localhost:3000`.
2. Load and activate the workflow.
3. Start chatting with the bot in the interface.

