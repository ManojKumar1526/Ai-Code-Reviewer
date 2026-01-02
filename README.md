
# 🚀 AI Code Reviewer


AI Code Reviewer is an open-source tool that helps developers automate code reviews using AI.
It analyzes code changes (diffs or full repositories) and provides actionable feedback to improve
code quality, consistency, and maintainability.

---

## ✨ Features

- AI-powered code review summaries and suggestions
- Supports reviewing git diffs or entire repositories
- Configurable review templates and policies
- GitHub Actions and CI integration
- Pluggable AI model backends (OpenAI, local LLMs, etc.)
- Optional automatic pull request comments
- Basic caching and rate-limit handling

---

## 🧰 Requirements

- Git
- Python 3.9+ or Node 14+ (depending on implementation)
- AI model API key (e.g. OPENAI_API_KEY)

---

## ⚡ Quick Start

### Clone and install

```bash
git clone https://github.com/ManojKumar1526/Ai-Code-Reviewer.git
cd Ai-Code-Reviewer
pip install -e .
