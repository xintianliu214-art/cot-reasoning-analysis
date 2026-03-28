# Chain-of-Thought Reasoning Analysis

This repository contains the data and materials for the term paper:

**"Evaluating Chain-of-Thought Prompting on Multi-Step Reasoning in Large Language Models"**

## 📊 Dataset
- 45 multi-step reasoning questions
- 3 categories:
  - Arithmetic (15)
  - Logical (15)
  - Commonsense (15)
- Adapted from GSM8K and StrategyQA

## ⚙️ Prompting Strategies
We evaluated three prompting methods:
1. **Baseline (Direct Prompting)**  
2. **Zero-shot Chain-of-Thought (CoT)**  
3. **Self-Consistency (SC)**  

All prompt templates are provided in `prompts.txt`.

## 📈 Results
- Results are stored in `results.csv`
- Each row contains:
  - Question ID
  - Ground truth answer
  - Model outputs (Baseline / CoT / SC)
  - Correctness labels

## 🔍 Reproducibility
All experiments were conducted using GPT-4o via OpenAI Playground.

## ⚠️ Note on AI Usage
Generative AI tools (GPT-4o, DeepSeek, Gemini) were used only for:
- language polishing
- formatting assistance

All experimental design, data, and analysis were conducted by the author.

## 📎 Repository Structure
```
dataset.csv # full dataset
results.csv # experimental results
prompts.txt # prompt templates
README.md # project description
```
