# OpenRouter Setup Guide

## Getting an API Key

Create an account on OpenRouter and generate an API key from the dashboard.

---

## Linux/macOS Setup

```bash
export OPENROUTER_API_KEY="your_api_key_here"
```

---

## Windows PowerShell Setup

```powershell
$env:OPENROUTER_API_KEY="your_api_key_here"
```

---

## Verify API Configuration

```bash
curl https://openrouter.ai/api/v1/models \
  -H "Authorization: Bearer YOUR_API_KEY"
```

---

## Model ID Examples

Canonical model ID:
```text
deepseek-r1
```

Provider-prefixed model ID:
```text
openrouter/deepseek-r1
```

---

Do not use real API keys in documentation examples.
