# 🦜 Chat SQL DB – Natural Language to SQL using LLM

Chat with your SQL database using Natural Language!

This project is a Streamlit-based application that allows users to query a SQL database (SQLite or MySQL) using plain English. It uses LangChain's SQL Agent with Groq's LLaMA 3 model to generate SQL queries dynamically and return results.

---

## 🚀 Features

- ✅ Ask questions in natural language
- ✅ Works with:
  - SQLite (local database)
  - MySQL (remote database)
- ✅ Uses LangChain SQL Agent
- ✅ Powered by Groq LLaMA 3.3 70B model
- ✅ Streamlit chat interface
- ✅ Streaming responses
- ✅ Tool usage visibility via callbacks

---

## 🧠 How It Works

1. User enters a question in plain English.
2. LangChain SQL Agent:
   - Understands the question
   - Inspects the database schema
   - Generates appropriate SQL query
3. The query is executed safely.
4. Results are returned to the user in natural language.

LLM does NOT guess — it reads schema, generates SQL, executes, and then explains results.

---
