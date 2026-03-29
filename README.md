
# 🤖 AI Blog Generator Agent using LangGraph

An advanced AI agent system that **automatically researches, plans, and writes blog posts** using a structured multi-agent pipeline powered by **LangGraph**.

---

## 🚀 Overview

This project demonstrates how to build an **autonomous AI content generation system** that mimics a real-world workflow:

1. 📡 Research a topic
2. 🧭 Plan the blog structure
3. ✍️ Generate content
4. 🔄 Refine and finalize output

---

## 🏗️ Architecture

The system follows a modular agent-based pipeline:

Start → Router → Research → Orchestrator → Worker → Reducer → End

### 🔹 Components:

- **Router**
  - Decides the flow of execution
  - Routes tasks to appropriate agents

- **Research Agent**
  - Gathers relevant information
  - Extracts insights and context

- **Orchestrator**
  - Plans the blog structure
  - Breaks tasks into smaller subtasks

- **Worker**
  - Generates content (sections of blog)
  - Uses LLM for writing

- **Reducer**
  - Combines outputs
  - Produces final polished blog

---

## ✨ Features

- ✅ Fully autonomous blog generation
- ✅ Modular multi-agent design
- ✅ Scalable architecture using LangGraph
- ✅ Research-driven content generation
- ✅ Easy to extend (add SEO agent, fact-checker, etc.)

---

## 🛠️ Tech Stack

- Python 🐍
- LangChain / LangGraph
- LLMs (OpenAI / HuggingFace)
- Streamlit (optional UI)

---

## 📂 Project Structure

├── agents/
│ ├── router.py
│ ├── research.py
│ ├── orchestrator.py
│ ├── worker.py
│ └── reducer.py
├── main.py
├── utils/
├── requirements.txt
└── README.md


---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/ai-blog-generator-langgraph.git
cd ai-blog-generator-langgraph
pip install -r requirements.txt
```

## ▶️ Usage
```bash
python main.py
```

Provide a topic and let the AI agent generate a complete blog automatically.


📌 Example Workflow

Input:

"Impact of AI on Healthcare"

Output:

Structured blog with:
Introduction
Key sections
Conclusion
Insights from research
🔥 Future Improvements
🧪 Fact-checking agent
🔍 SEO optimization module
🌐 Web search integration
🎨 Blog formatting (Markdown/HTML)
📊 Analytics & readability scoring
🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a PR.

📜 License

MIT License

👨‍💻 Author

Nitesh Raghuwanshi
Machine Learning Engineer | AI Builder