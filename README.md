# 🌟 Nour — Bilingual AI Life Coach

Nour is a **bilingual (Arabic/English) AI Life Coach** designed to help users build better habits, track goals, and maintain daily accountability using modern LLM-powered systems.

The system runs locally using **Ollama** and integrates memory, goal tracking, and habit tracking to simulate a real personal coach experience.

---

## 🚀 Features

- 🧠 Persistent memory (remembers user history and context)
- 🎯 Goal tracking system (add, update, and monitor progress)
- 📅 Habit tracking with streak system
- 🌅 Daily AI check-ins (mood, energy, progress)
- 🌍 Fully bilingual (Arabic / English auto-detection)
- 💬 Conversational AI coaching style
- 🧩 Local LLM inference using Ollama

---

## 🧠 AI Concept Behind the Project

Nour is built as a lightweight **Agentic AI system**, combining:

- LLM-based reasoning (Qwen via Ollama)
- Structured memory system (JSON-based persistence)
- Tool-like functions (goals, habits, tracking)
- Prompt-driven coaching behavior
- Stateful conversation design

This simulates a simple **autonomous coaching agent** that adapts to the user over time.

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Ollama (Local LLM Runtime)
- Qwen 3 / LLM models
- JSON-based memory system
- Basic Agentic AI design patterns

---

## 📁 Project Structure

app.py           # Streamlit UI coach.py         # AI logic (LLM + prompts) memory.py        # User memory system tracker.py       # Goals & habits system data/            # Stored user data (JSON files)

---

## ⚙️ How to Run

### 1. Install dependencies
```bash
pip install streamlit ollama

2. Install and run Ollama

ollama serve

3. Pull model

ollama pull qwen3:8b

4. Run the app

streamlit run app.py


---

💡 Example Use Cases

Personal productivity coaching

Habit building assistant

Daily motivation and reflection tool

AI-powered self-improvement tracker



-

🔥 Why this project matters

This project demonstrates:

Real-world Agentic AI design

Integration of LLMs in applications

Memory + state management in AI systems

Practical RAG-like behavior (context awareness)

Full-stack AI application development



---

📌 Future Improvements

Add vector database memory (ChromaDB / FAISS)

Upgrade to LangChain / LangGraph agents

Add authentication system

Cloud deployment (Docker / HuggingFace Spaces)

Voice assistant integration (STT/TTS)
