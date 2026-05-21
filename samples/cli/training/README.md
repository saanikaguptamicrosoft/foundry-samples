# Training Job Templates

This directory contains starter templates for submitting training jobs in Azure AI Foundry using the Azure Developer CLI (azd) training extension (`azure.ai.training`).

The goal is a code-first, automatable CLI workflow for custom training jobs in Foundry, optimized for ML engineers and data scientists who prefer terminal workflows and need repeatable execution.

When you run `azd ai training init` with a template flag, these templates are pulled locally to provide sample configurations for your training jobs:

```bash
azd ai training init -t <template-url>
```