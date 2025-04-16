# 🧠 SQL Prompt Generator for LLMs

This tool helps you generate tailored prompt instructions for Large Language Models (LLMs) like ChatGPT or GitHub Copilot. It assists in building PostgreSQL functions that follow your organization's data architecture, including:

✅ Wrapper & core function pattern  
✅ Mutation logging using Debezium-style audit entries  
✅ Context-aware generation (entity name, DDL, view type)  

## 🔧 How It Works

1. Fill out the form (entity name, input type, view, table, and DDL)
2. Click "Generate Prompt"
3. Copy the result and paste it into ChatGPT or another LLM to get SQL code suggestions

## 🚀 Hosted Version

You can access the generator live at:  
👉 https://evoludigit.github.io/sql-prompt-generator/

## 📁 Project Structure

```
index.html       # Main frontend file (static)
README.md        # Project overview and usage guide
```

## 🛠️ Tech Stack

- HTML + JavaScript (no frameworks)
- Hosted via GitHub Pages

## ✨ Example Use Case

Generate a pair of PostgreSQL functions for an entity `location`, using your DDL and audit log logic, ready for integration into your backend or DevOps pipelines.
