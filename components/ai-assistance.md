---
title: AI Assistance
---

# AI Assistance

The extension can use language and vision-language models to generate table captions and alt text respectively.

## Configuration
- Open `Settings > Settings Editor > A11y Checker Settings` in JupyterLab.
- Provide API endpoint, API key, and model name.

```{warning}
Do not include sensitive data in notebooks. API calls are user-configured.
```

## Scope
- Suggestions appear only when the AI option is enabled in certain “fix interfaces” such as table caption and alt-text generation
- Users review AI suggestions and make edits if required before applying those changes to the notebook
