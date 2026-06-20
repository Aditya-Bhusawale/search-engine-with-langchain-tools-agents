# 🔎 Search Engine with LangChain Tools & Agents

## Overview

Search Engine with LangChain Tools & Agents is an AI-powered search assistant built using LangChain, Groq LLM, and multiple external tools. The application intelligently selects the most appropriate tool to answer user queries, enabling access to web search, Wikipedia knowledge, and research papers.

## Features

* 🌐 Web Search using DuckDuckGo
* 📚 Wikipedia Search for general knowledge queries
* 📄 Arxiv Search for research papers and academic content
* 🤖 AI Agent powered by LangChain
* ⚡ Groq Llama 3.3 70B model for fast responses
* 🎨 Interactive Streamlit user interface
* 🔍 Automatic tool selection based on user queries

## Tech Stack

* Python
* Streamlit
* LangChain
* Groq
* DuckDuckGo Search
* Wikipedia API
* Arxiv API

## Project Workflow

1. User enters a query in the Streamlit interface.
2. LangChain Agent receives the query.
3. Agent analyzes the question.
4. Agent selects the most suitable tool:

   * DuckDuckGo → Internet Search
   * Wikipedia → General Knowledge
   * Arxiv → Research Papers
5. Tool retrieves relevant information.
6. Groq LLM processes the retrieved content.
7. Final answer is displayed to the user.

## Installation

```bash
pip install streamlit
pip install langchain
pip install langchain-community
pip install langchain-groq
pip install wikipedia
pip install arxiv
pip install ddgs
pip install python-dotenv
```

## Environment Variables

Create a `.env` file and add:

```env
GROQ_API_KEY=your_groq_api_key
```

## Run the Application

```bash
streamlit run app.py
```

## Example Queries

* What is LangChain?
* Who is Elon Musk?
* Explain Retrieval-Augmented Generation (RAG).
* Find recent research papers on Transformers.
* Latest developments in Artificial Intelligence.

## Repository Structure

```text
├── app.py
├── .env
├── requirements.txt
├── README.md
```

## Future Enhancements

* Add chat history support
* Integrate Tavily Search API
* Multi-agent architecture
* Research paper summarization
* Export search results to PDF

## Author

Aditya Gangadhar Bhusawale
Computer Engineering Student
