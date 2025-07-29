# LangChain Structured Chat Agent with Tools (Wikipedia + Time)

This project is a simple structured chat agent built with [LangChain](https://github.com/langchain-ai/langchain) and [OpenAI GPT-4o](https://platform.openai.com/docs/models/gpt-4o). The agent can:

- Remember past messages using memory
- Answer questions using Wikipedia
- Return the current time
- Interact in a conversational loop

## Features

- Uses `ConversationBufferMemory` to store context
- Uses `structured-chat-agent` prompt from LangChain Hub
- Integrates tools like:
  - `Time`: gets current time
  - `Wikipedia`: fetches brief summaries from Wikipedia
- Error handling for tool calls and parsing issues

## Project Structure

```shell
.
├── main.py         # Main script to run the agent
├── .env            # Store your OpenAI API key here
└── README.md       # Project documentation
