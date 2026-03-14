# Software Concepts — Explained Visually

A collection of interactive, single-page explainers for software engineering and LLM concepts.

## Live site

GitHub Pages URL: https://phirmware.github.io/software-concepts-explained-visually/

## Included explainers

- **How LLMs Work** (`how-llms-work.html`)
- **How LLM Training Works** (`llm-training.html`)
- **Server-Sent Events** (`sse.html`)
- **QLoRA Fine-tuning** (`qlora-fine-tuning.html`)

## Project structure

- `index.html` — Landing page linking to all available explainers and upcoming topics
- `how-llms-work.html` — Interactive walkthrough of LLM fundamentals
- `llm-training.html` — Interactive breakdown of the LLM training pipeline
- `sse.html` — Interactive study guide for Server-Sent Events
- `qlora-fine-tuning.html` — Interactive explainer of QLoRA and low-memory fine-tuning

## Local development

This project is static HTML/CSS/JS and can be run directly.

Option 1: open `index.html` in your browser.  
Option 2 (recommended): serve the folder with any static server for best compatibility:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

