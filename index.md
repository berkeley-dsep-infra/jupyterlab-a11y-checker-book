---
title: Introduction
---

## JupyterLab-A11y-Checker

JupyterLab-A11y-Checker is a JupyterLab extension that helps authors detect and fix common accessibility issues in Jupyter Notebooks, aligning with WCAG 2.1 AA guidelines. It combines the strengths of axe-core, a widely used accessibility engine, with custom notebook-specific detection algorithms that address issues axe cannot reliably cover in JupyterLab. Specifically the extension can:

- Detect accessibility issues in images, headings, tables, and links(see [Rules](components/rules#rules-index)).
- Apply targeted fixes to those issues via guided interfaces (see [Fix Interfaces](components/fix#fix-ui-index)).
- Optionally use AI assistance (LLM / VLM) to draft suggestions for certain usecases.

Repository: [Jupyterlab-a11y-checker on GitHub](https://github.com/berkeley-dsep-infra/jupyterlab-a11y-checker)

```{figure} images/overview.png
:name: fig-overview
:alt: Screenshot of the a11y checker panel in JupyterLab

The extension detects accessibility issues in a notebook and provides notebook authors with assistance to fix those issues.
```

The extension focuses on the following issues,
- Missing Alternative Text (Alt Text) for images in Markdown cells.
- Notebook Lacks a Primary Heading (H1), which should serve as the notebook's main title.
- Multiple H1 Headings present in the notebook (should only be one for the title).
- Duplicate Heading Text across different sections of the notebook.
- Empty Heading elements (e.g., ## ) identified.
- Missing Table Headers (row or column headers) in Markdown tables.
- Missing Table Caption to summarize the table's content.
- Missing Table Scope attributes for table headers, required for complex data tables.
- Insufficient Color Contrast for text within images or image outputs.
- Indiscernible Link Text (e.g., "click here," or bare URLs) in Markdown cells.