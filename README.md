# 🤖 Gemini Agent with OpenAI-Compatible Interface

This project demonstrates a frontend agent that interacts with Google's Gemini model via an OpenAI-compatible agent system, using the `uv` package manager.

---

## 🚀 Features

- Agent-based architecture using `Runner`, `Agent`, and `OpenAIChatCompletionsModel`
- Connects to Gemini API (manually adapted to OpenAI-style interface)
- Uses `uv` for dependency management
- Supports `.env`-based API key configuration

---

## 🛠️ Requirements

- Python 3.8+
- [`uv`](https://github.com/astral-sh/uv) package manager
- Gemini API access
- Custom wrapper or adapter for OpenAI-style use

---

## 📦 Installation

```bash
# Install dependencies
uv pip install python-dotenv
