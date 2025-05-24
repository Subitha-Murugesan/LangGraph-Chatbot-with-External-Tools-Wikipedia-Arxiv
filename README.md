# LangGraph Chatbot with External Tools (Wikipedia & Arxiv)

This project demonstrates how to build a stateful chatbot using **LangGraph** and **LangChain**, backed by the **Groq Gemma2-9b-It LLM**. The chatbot can intelligently call external knowledge tools like **Wikipedia** and **Arxiv API** to answer user queries it cannot answer on its own.

## Features

- Stateful conversation management with LangGraph
- Integration with Groq LLM via LangChain
- External tool support for Wikipedia and Arxiv queries
- Conditional routing: chatbot first tries to answer, else falls back to external tools
- Easy extension with more tools

## Setup

1. Clone the repo.
2. Create a `.env` file with your Groq API key:


GROQ\_API\_KEY=your\_groq\_api\_key\_here


## Usage

Run the notebook or script and enter messages to chat with the bot. The bot will respond using its knowledge and external tools if needed.

Example queries:

* "Who is the chancellor of Germany?"
* "What is the latest research on quantum computing?"
* "Who is the actor in the movie Inception?"

Chatbot contacting Arxiv tool for relevant response
![image](https://github.com/user-attachments/assets/b9963a75-a2cf-44d3-9dcc-70494fc57a42)

Chatbot contacting Wikipedia tool for relevant response

![image](https://github.com/user-attachments/assets/cadde801-d88e-44ae-a930-572cabcb7438)


