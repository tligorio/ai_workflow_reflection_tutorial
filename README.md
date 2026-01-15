# Simple AI Workflow with Reflection using OpenRouter

In this demo, we build a simple AI workflow that demonstrates the reflection pattern using three LLM personas working together to produce a polished report.

The workflow consists of three stages:
1. **Report Writer** (think journalist) — Generates an initial report based on a user-provided topic
2. **Critic** (think editor) — Provides detailed critique and improvement suggestions
3. **Reviser** (think senior reporter) — Takes the original report and critique to produce a polished final version

This pattern illustrates how multiple LLM calls can be orchestrated to improve output quality through self-reflection and revision.

## Getting Started

### Option 1: Run in Google Colab (Recommended for quick start)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tligorio/ai_workflow_reflection_tutorial/blob/main/AI_Workflow_with_Reflection.ipynb)

Click the badge above to open the notebook directly in Google Colab.

### Option 2: Run Locally

For local installation, clone this repository and follow the instructions in [SETUP.md](SETUP.md).
