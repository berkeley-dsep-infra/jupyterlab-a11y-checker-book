---
title: Using the a11y-checker extension
---

# Using the a11y-checker extension

## Scanning for accessibility issues in a Jupyter Notebook
- Launch the notebook which needs to be audited in the JupyterLab interface
- Click the "Digital accessibility icon" on the side bar to launch the user interface of the extension
- Click "Analyze Notebook" option to view the existing accessibility issues in the notebook
- Each issue will be categorized based on the issue type reported


## Fixing accessibility issues in a Jupyter Notebook
- Image alt text: Enter alt text (AI suggestion optional).
- Headings: ensure a single H1, correct order, and non-empty content.
- Tables: add header(s), caption, and set `scope`.
- Color: note contrast issues and adjust content or theme.

See [](components/rules) and [](components/fix) for details.

## Configuring AI assistance
- Go to `Settings > Settings Editor > A11y Checker Settings`.
- Provide API endpoint, key, and model.

```{note}
Models are optional and used only within certain fix interfaces.
```
