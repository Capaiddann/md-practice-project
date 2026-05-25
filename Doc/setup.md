# Setup Guide

How to install and run the Lead Gen Agent system.

## Requirements

- Python 3.11+
- VS Code
- API Keys (Claude, Google Maps)

## Installation

**Step 1 — Clone the project:**

```bash
cd "C:\Users\IT Frnd"
git clone https://github.com/Capaiddann/md-practice-project.git
```

**Step 2 — Install dependencies:**

```bash
pip install -r requirements.txt
```

**Step 3 — Setup your API keys:**

Create a `.env` file in the project folder:
ANTHROPIC_API_KEY=your_key_here
GOOGLE_MAPS_API_KEY=your_key_here

**Step 4 — Run the agent:**

```bash
python agent.py
```

## Common Errors

| Error | Fix |
|-------|-----|
| Module not found | Run `pip install -r requirements.txt` |
| API key invalid | Check your `.env` file |
| Path not found | Use quotes around folder path |

## Notes
- Never share your `.env` file
- Always use `--break-system-packages` with pip on Windows
- Copy `.env` to every new project

