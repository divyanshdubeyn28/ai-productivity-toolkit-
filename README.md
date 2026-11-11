<div align="center">

# 🚀 AI Productivity Toolkit

*Transform your daily workflow using Advanced Prompt Engineering, Structured JSON Outputs, and Automated LLM Scripts.*

[![GitHub License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-teal.svg)](https://www.python.org/)
[![Gemini API](https://img.shields.io/badge/Powered%20by-Gemini%20API-orange.svg)](https://ai.google.dev/)

</div>

---

## 📖 Introduction
Welcome to the **AI Productivity Toolkit**! Whether you are a developer, student, or professional, this repository helps you leverage Large Language Models (LLMs) effectively. Instead of writing casual prompts, this toolkit provides **battle-tested, structured prompt templates and Python automation scripts** to save time and automate repetitive tasks.

---

## 🎯 What You Will Find Inside?

### 1. 📂 Reusable Prompt Templates (`/prompts`)
Inside the `prompts/` folder, you will find production-ready templates built using standard prompt engineering principles (Roles, Contexts, Instructions, and Constraints):
* **[Summarizer (`summarizer.md`)](prompts/summarizer.md):** Distills lengthy articles, reports, or meeting notes into structured 1-sentence theses and key bullet points.
* **[Email Drafter (`email_drafter.md`)](prompts/email_drafter.md):** Converts rough bullet points into polished, professional emails with clear call-to-actions.
* **[JSON Extractor (`json_extractor.md`)](prompts/json_extractor.md):** Forces AI to extract unstructured text data into strictly formatted JSON objects for backend parsing.

### 2. 📓 Executable Python Script (`/colab`)
* **[Colab Demo (`ai_productivity_demo.ipynb`)](colab/ai_productivity_demo.ipynb):** A plug-and-play Jupyter notebook demonstrating **Few-Shot Prompting** for sentiment classification and programmatic **Structured JSON Outputs** using the Gemini API.

---

## 🗂️ Repository Structure

```text
ai-productivity-toolkit/
│
├── 📁 prompts/               # Ready-to-use Markdown prompt templates
│   ├── 📄 summarizer.md      # Long-form text summarization template
│   ├── 📄 email_drafter.md   # Professional email generator template
│   └── 📄 json_extractor.md  # Strict schema-enforced data extractor
│
├── 📁 colab/                 # Interactive Python code
│   └── 📓 ai_productivity_demo.ipynb  # Google Colab notebook for API execution
│
└── 📄 README.md              # Documentation (You are here!)
