---
title: Introduction
---

## JupyterLab-A11y-Checker

JupyterLab-A11y-Checker is a JupyterLab extension that helps authors detect and fix common accessibility issues in Jupyter Notebooks, aligning with WCAG 2.1 AA guidelines. It combines the strengths of axe-core, a widely used accessibility engine, with custom notebook-specific detection algorithms that address issues axe cannot reliably cover in JupyterLab. Specifically the extension can:

- Detect accessibility issues in images, headings, tables, and links(see [Rules](components/rules#rules-index)).
- Apply targeted fixes to those issues via guided interfaces (see [Fix Interfaces](components/fix#fix-ui-index)).
- Optionally use AI assistance (LLM / VLM) to draft suggestions for certain usecases.

Repository: [jupyterlab-a11y-checker on GitHub](https://github.com/berkeley-dsep-infra/jupyterlab-a11y-checker)

```{figure} images/overview.png
:name: fig-overview
:alt: Screenshot of the a11y checker panel in JupyterLab

The extension detects accessibility issues in a notebook and provides notebook authors with assistance to fix those issues.
```

## Components
- [Rules](components/rules)
- [Fix Interfaces](components/fix)
- [AI Assistance](components/ai-assistance)

## More
- [Examples Intro](examples/intro)
