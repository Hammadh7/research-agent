# Literature Review agent

Core backend logic for a **multi-agent literature-review assistant** powered by the [AutoGen AgentChat stack](https://microsoft.github.io/autogen) (⩾ v0.4).  
This module coordinates a **two-agent team** to automatically search, filter, and summarize research papers from **arXiv** into a concise **Markdown-formatted literature review**.  

---

## 🚀 Features

- **Automated Paper Discovery** – Queries arXiv via the official `arxiv` Python API.  
- **Agentic Workflow** – Two collaborating LLM agents:  
  - 🕵️ **Search Agent** – Crafts queries, calls arXiv, and filters the results.  
  - ✍️ **Summarizer** – Writes a structured Markdown review.  
- **Portable** – Self-contained design, easily embedded in:
  - Streamlit dashboards  
- **Streaming Output** – Yields conversation messages incrementally for real-time display.  

---

## 📦 Installation

1. Clone the repository  
2. Install dependencies:  


