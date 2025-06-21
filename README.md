# 🤖 Functional-Al-Agent-with-Tool-Use-and-Database-Context

A modular, offline-capable AI assistant built step-by-step in Google Colab. This smart agent can **perform calculations**, **run SQL queries**, **simulate web searches**, **generate LLM-based responses**, and **store conversation history** — all without relying on an external backend.

---


## 🚀 AI Agent 

🔗 **Open in Google Colab**: [🔗 Google Colab Link](https://colab.research.google.com/drive/1donMsByIpvIQSIaNOblMloweH4PvXVHf?usp=sharing)


## 📌 Project Overview

This AI Agent demonstrates how to build an intelligent assistant using:

- ✅ **Python (Google Colab compatible)**
- ✅ **SQLite** for storing product & conversation data
- ✅ **Transformers (GPT-2)** for offline text generation
- ✅ **Simulated web search & SQL execution**
- ✅ **Modular architecture** (cell by cell)

---

## 🚀 Features

| Feature                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 🧮 Calculator           | Handles math expressions, percentages like "25% of 1600"                    |
| 🔍 Web Search           | Simulates AI/ML search queries inside Colab (no internet needed)           |
| 📊 SQL Querying         | Converts natural language to SQL and runs it on a local SQLite database     |
| 💾 Memory               | Stores and retrieves previous conversations for context awareness           |
| 🧠 LLM Integration      | Uses GPT-2 locally (via Hugging Face Transformers) to generate responses     |
| 🧪 Interactive Chat     | Offers a simple command-line chat session right inside Colab                |

---

## 🧱 Architecture

🏗️ AI AGENT ARCHITECTURE

---
User Input → Intent Classification → Tool Selection → Processing → Response


### 📦 COMPONENTS:

├── DatabaseManager - SQLite database operations

├── LLMManager - Language model integration

├── CalculatorTool - Mathematical operations

├── WebSearchTool - Search functionality (simulated)

├── SQLTool - Natural language to SQL conversion

└── AIAgent - Main orchestrator

### 🔄 WORKFLOW:
User Input → Intent Classification → Tool Selection → Processing → Response

### 📊 DATABASE SCHEMA:
├── chat_memory (conversations)

├── products (product catalog)

└── sales (transaction data)


---

## 🛠️ Setup Instructions (Google Colab)

1. Open a new Google Colab notebook.
2. Copy each code cell from this repo (Cells 1–12) into Colab, one by one.
3. Run cells **in order** to set up the tools, data, and logic.
4. Start chatting using:

```python
start_interactive_chat()

```

### 🔍 Example Queries
#### Calculator
-> What's 35% of 1500?

-> 15 + 30 * 2

#### Web Search
-> Search latest AI frameworks

-> Find AI tools

#### Database Queries
-> Show all products

-> What are total sales for Laptop A?

-> List recent sales

-> Follow-up

What about that total again?

#### ✅ Status
 -Fully offline-compatible

 -No OpenAI key required

 -Pre-loaded sample data

 -Easy to extend and customize



