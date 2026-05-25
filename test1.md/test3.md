# Agent Comparison

Comparing all AI models for my agents.

## Model Comparison

| Model        | Speed  | Cost   | Best For              |
|--------------|--------|--------|-----------------------|
| Claude Haiku | Fast   | Cheap  | Simple extraction     |
| Claude Sonnet| Medium | Medium | Reasoning tasks       |
| Claude Opus  | Slow   | costly | Complex decisions     |
| GPT-4        | Medium | costly | General tasks         |
| Gemini       | Fast   | Cheap  | Google integration    |

## When To Use Each

### Use Haiku When:
- Extracting data from websites
- Simple yes/no decisions
- High volume tasks

### Use Sonnet When:
- Writing emails
- Analysing leads
- Medium complexity tasks

### Use Opus When:
- Complex business decisions
- Strategy planning
- Critical tasks only

## Example Code

```python
import anthropic

client = anthropic.Anthropic()

# Use Haiku for simple tasks
response = client.messages.create(
    model="claude-haiku-4-5",
    max_tokens=100,
    messages=[{"role": "user", "content": "Extract company name"}]
)
```

Press `Ctrl+S` → check preview → tell me when done! 👀

**What this tests:** Tables with alignment, nested `###` headings, code blocks with real Python.