# DATASCI 350 Quiz 03 — Local LLMs and Cloud Data Analysis

A data-science computing project covering two workflows: customizing a local LLM with Ollama and running a Python traffic-analysis script in a cloud-computing context.

## What it demonstrates

- Local LLM experimentation with Ollama and a custom `Modelfile`
- Prompt/personality design for a small custom chatbot
- Python data analysis with pandas, matplotlib, and seaborn
- Basic cloud/EC2 workflow documentation and reproducible command logging

## Project structure

```text
ollama/
├── Modelfile      # custom local model configuration
└── ollama.md      # commands and example interactions

aws/
├── traffic_analysis.py   # Python analysis script
├── website_traffic.txt   # input dataset
├── traffic_analysis.png  # generated visualization
└── os.txt                # environment notes
```

## Activity 1: Ollama model

The `ollama/` folder defines a custom chatbot named `sarcastic` using `llama3.2:1b` as the base model. The `Modelfile` sets behavior and tone through a detailed system prompt and generation parameters.

Example commands:

```bash
ollama pull llama3.2:1b
ollama create sarcastic -f ollama/Modelfile
ollama run sarcastic
```

## Activity 2: traffic analysis

The `aws/traffic_analysis.py` script reads a text dataset, calculates traffic summary statistics, and saves a plot.

```bash
cd aws
python traffic_analysis.py
```

## Portfolio note

This repo is strongest as evidence of AI-assisted programming literacy: it combines local model setup, prompt design, Python analysis, and cloud workflow practice.
