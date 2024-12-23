# load-summarize-chain
Lesson about using LangChain's load_summarize_chain with Ollama and long texts to summarize

In this repo, we explore two approaches of text summarization: map-reduce and refine.

## Table of Contents
1. [Introduction](#introduction)
2. [Approaches](#approaches)
    - [Map-Reduce](#map-reduce)
    - [Refine](#refine)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction
This repository demonstrates how to use LangChain's `load_summarize_chain` with Ollama to summarize long texts efficiently.

## Approaches
### Map-Reduce
The map-reduce approach involves breaking down the text into smaller chunks, summarizing each chunk, and then combining these summaries into a final summary.

### Refine
The refine approach iteratively improves the summary by refining it through multiple passes over the text.

## Setup environment
To install the necessary dependencies, run:
```bash
pip install -r requirements.txt
```
## Tools you will use
- `Ollama` to run local LLM API
- `Llama 3.2-3B` from Meta, to use as AI brain. See on Ollama page.
- `LangChain` as framework for LLM app
- `tiktoken` library to estimate token counts

## Sharing & Crediting

> Feel free to copy and distribute, but we appreciate you giving us credits.


## ⛓️Connect with Us:

👍 Like | 🔗 Share | 📢 Subscribe | 💬 Comments | ❓ Questions

[LinkedIn](www.linkedin.com/company/casedonebyai) <br>
[YouTube](www.youtube.com/@CaseDonebyAI) <br>
[Facebook](www.facebook.com/casedonebyai) <br>
[TikTok](www.tiktok.com/@casedonebyai) <br>
[Github](www.github.com/casedone) <br>
[SubStack](casedonebyai.substack.com)