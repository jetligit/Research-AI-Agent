🤖 Research AI Agent

A Python-based AI research assistant built with LangChain and OpenAI’s GPT-4o-mini. This agent helps generate research summaries on any topic, including references to sources and tools used.

🌟 Features
Generates structured research summaries including:
- Topic
- Summary of key points
- Sources referenced
- Tools used
Uses LangChain to manage conversation flow and prompt formatting
Wraps outputs in a strict Pydantic schema to ensure clean, structured results
Can leverage Wikipedia and DuckDuckGo using tools for extended research
Saves research information to a txt file

🛠️ Technologies Used
Python 3
LangChain – for prompt management and agent orchestration
OpenAI GPT-4o-mini – for generating natural language research summaries
Pydantic – for structured output parsing
