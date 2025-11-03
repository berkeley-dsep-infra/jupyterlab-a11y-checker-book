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
* **Image alt text:** Prompts user with an input field to add the descriptive alt text directly. Provides an option to use a vision model to generate an alternative text that can be inserted as alt-text to images in markdown.
* **Headings:** Inserts a new H1 heading cell at the top of the notebook upon user confirmation.
* **Multiple H1 Headings:** Offers a one-click demotion of secondary H1s to H2 headings.
* **Duplicate Heading Text across sections:** Highlights the heading text and prompts the user to edit/clarify the content.
* **Missing Table Headers in Markdown tables:** Guides the user to explicitly define row or column headers in the table markdown.
* **Missing Table Caption to summarize the table:** Prompts user with an input field to add the required table caption text. Provides the option to use language models to generate summary of the table and insert it as table caption.
* **Missing Table Scope attributes for headers:** Offers a button to inject scope=“col” or scope=“row” attributes to header cells.
* **Indiscernible Link Text in Markdown cells:** Highlights the link and prompts the user to replace the bare URL/vague text with clear anchor text.
* **Color Contrast Issues:** Identifies images with color contrast issues and prompts users to use images without color contarast violations.

## Configuring AI assistance
- Go to `Settings > Settings Editor > A11y Checker Settings`.
- Provide API endpoint, key, and model.

```{note}
Using language and vision models are optional for table caption and alt-text generation respectively
```
