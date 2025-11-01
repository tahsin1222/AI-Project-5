# AI-Project-5
🧠 AI Research Assistant

A modular AI-powered research assistant built using LangChain, Anthropic’s Claude, and Pydantic.
This project allows you to automatically research a topic, summarize findings, and store structured results — all through tool-assisted reasoning.

🚀 Features

🤖 Intelligent Research Automation – Uses Anthropic’s Claude model to understand queries and generate research responses.

🧩 Tool Integration – Dynamically calls tools for:

search_tool: Performs online searches

wiki_tool: Gathers information from Wikipedia

save_tool: Stores research results

🧱 Structured Output – Returns responses in a clean, validated format using Pydantic.

🧠 LangChain Agent Framework – Handles reasoning, tool usage, and result parsing.

🧰 Tech Stack

Python 3.10+

LangChain

Anthropic (Claude 3.5 Sonnet)

Pydantic

dotenv (for environment variables)

⚙️ How It Works

The assistant prompts the user for a research query.

It uses Claude 3.5 Sonnet as the reasoning model.

LangChain’s AgentExecutor dynamically decides which tools to use.

🧠 Future Improvements

 Add OpenAI GPT-4o support

 Add citation extraction

 Integrate PDF export for research summaries

 Add a web-based UI using Streamlit or React
