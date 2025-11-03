---
title: Troubleshooting issues with the a11y-checker extension
---

# Troubleshooting

## The extension does not appear in my JupyterLab interface
- Check whether the extension is installed in your image: `pip list | grep a11y`
- Rebuild/refresh JupyterLab if building from source

## Getting error messages instead of getting suggestions from AI models
- Ensure settings (endpoint, key, model) are configured. You can check that by accessing "Settings -> A11y Checker Settings -> Language Model Settings" or "Settings -> A11y Checker Settings -> Vision Model Settings" 
# - Check network access to your API endpoint if you 
- Try refreshing the page after updating your model configurations

If the issue with language model persists then reach out to a11y-checker@berkeley.edu for support.