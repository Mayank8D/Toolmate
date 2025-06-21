<p align="center">
  <img src="https://img.shields.io/badge/AI-Workflow%20Planner-blueviolet?style=for-the-badge&logo=python" alt="AI Workflow Planner"/>
  <br/>
  <img src="https://img.icons8.com/fluency/96/robot-2.png" width="80" alt="Toolmate Icon"/>
  <h1 align="center">🤖 Toolmate: Student AI Function Planner</h1>
  <p align="center">
    <b>Plan, automate, and execute data workflows using AI-powered function orchestration.</b><br/>
    <i>Streamline your data tasks with a natural language interface and a rich set of tools.</i>
  </p>
</p>

---

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License"></a>
  <a href="#"><img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg?style=flat-square&logo=python" alt="Python"></a>
  <a href="#"><img src="https://img.shields.io/badge/Streamlit-UI-orange.svg?style=flat-square&logo=streamlit" alt="Streamlit"></a>
  <a href="#"><img src="https://img.shields.io/badge/Powered%20by-Gemini-2.0-blueviolet?style=flat-square" alt="Gemini"></a>
</p>

---

## ✨ Overview

**Toolmate** is an AI-powered workflow planner that helps users break down complex data and automation tasks into actionable steps using a curated set of function tools. With a user-friendly Streamlit interface and robust CLI, Toolmate leverages LLMs (like Gemini) to translate your requests into executable plans.

- 🧠 **AI Planning:** Converts natural language queries into step-by-step function calls.
- 🛠️ **Extensible Toolset:** 30+ built-in tools for data extraction, transformation, summarization, communication, and more.
- 📊 **Modern UI:** Interactive Streamlit app for planning, reviewing, and updating workflows.
- ⚡ **CLI Support:** Command-line interface for quick, scriptable access.
- 🔒 **Secure:** API keys and secrets managed via environment files.

---

## 🚀 Features

- **Natural Language to Workflow:** Just describe your task; Toolmate plans the function sequence.
- **Rich Tool Library:** Includes PDF/text extraction, CSV parsing, summarization, email/SMS, translation, and more.
- **Interactive Plan Editing:** Review, update, and version your workflow plans in the UI.
- **Debug & Transparency:** View raw LLM prompts and responses for full transparency.
- **Easy Extensibility:** Add new tools by editing a single JSON file.

---

## 🖥️ Demo

<p align="center">
  <img src="https://user-images.githubusercontent.com/placeholder/demo.gif" alt="Toolmate Demo" width="700"/>
  <br/>
  <i>Demo: Describe your workflow, get an AI-generated plan, and review/edit steps interactively.</i>
</p>

---

## 🏗️ Project Structure

```
mate/
  core/        # Core logic: prompt building, API calls, tool schema
  data/        # Tool definitions (JSON), sample prompts
  ui/          # Streamlit UI components
  main.py      # CLI entry point
  requirements.txt
  open.env     # API keys and environment variables
```

---

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/toolmate.git
   cd toolmate
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**
   - Copy `open.env.example` to `open.env` and add your API keys (e.g., `GEMINI_API_KEY`).

---

## 🏃 Usage

### 🌐 Streamlit Web App

```bash
streamlit run ui/ui_app.py
```

### 🖥️ Command-Line Interface

```bash
python main.py
```

---

## 🧩 Adding/Editing Tools

- Edit `data/function_tools.json` to add new function tools or update existing ones.
- Each tool includes a name, input/output schema, description, and keywords.
- No code changes required for new tools—just update the JSON!

---

## 📦 Dependencies

- `streamlit`, `openai`, `python-dotenv`, `scikit-learn`, `pillow`, `graphviz`, `requests`

---

## 🤝 Contributing

Pull requests and feature suggestions are welcome! Please open an issue to discuss your ideas.

---

## 📄 License

[MIT License](LICENSE)

---

## 🙏 Acknowledgements

- Powered by [Google Gemini](https://ai.google/discover/gemini/) and [Streamlit](https://streamlit.io/)
- Inspired by the need for accessible, AI-driven workflow automation for students and professionals.

---

> _"Let AI handle the busywork, so you can focus on what matters."_ 
