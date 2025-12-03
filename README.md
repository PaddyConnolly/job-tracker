# 🎯 Job Tracker

[![CI](https://github.com/PaddyConnolly/job-tracker/actions/workflows/ci.yml/badge.svg)](https://github.com/PaddyConnolly/job-tracker/actions/workflows/ci.yml)

A self-hosted application that tracks job listings across company career pages using LLM-powered selector extraction.

## 🚀 Setup

1. Clone the repository:
```bash
   git clone https://github.com/YOUR_USERNAME/job-tracker.git
   cd job-tracker
```

2. Install [uv](https://docs.astral.sh/uv/getting-started/installation/) if you haven't already.

3. Install dependencies:
```bash
   uv sync
```

4. Install pre-commit hooks:
```bash
   uv run pre-commit install
```

## 🛠️ Development

Run linting:
```bash
uv run ruff check .
```

Run type checking:
```bash
uv run mypy src
```

Run tests:
```bash
uv run pytest
```
