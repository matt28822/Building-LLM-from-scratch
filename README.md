# Build a Large Language Model (From Scratch) — My Implementation

My chapter-by-chapter implementation of [Sebastian Raschka's](https://sebastianraschka.com/llms-from-scratch/) book *Build a Large Language Model (From Scratch)*. I coded each component by hand in Python and PyTorch — tokenization, attention, the full GPT architecture, pretraining, and fine-tuning — to understand how modern LLMs work under the hood rather than treating them as black boxes.

## Why I built this

I wanted to move beyond calling LLM APIs and actually understand what happens inside a model like GPT. Coding it from scratch — from text tokens all the way to an instruction-following chatbot — was the most effective way to do that.

## What's inside

| Chapter | Topic | Status |
|---------|-------|--------|
| 01 | Understanding LLMs (concepts) | ⬜ Not started |
| 02 | Working with text data — tokenization, embeddings | ⬜ Not started |
| 03 | Coding attention mechanisms | ⬜ Not started |
| 04 | Implementing a GPT model from scratch | ⬜ Not started |
| 05 | Pretraining on unlabeled data | ⬜ Not started |
| 06 | Fine-tuning for classification (spam classifier) | ⬜ Not started |
| 07 | Fine-tuning to follow instructions (chatbot) | ⬜ Not started |
| App. A | Intro to PyTorch | ⬜ Not started |

> Update the status column as you go: ⬜ Not started → 🔨 In progress → ✅ Done

## Key results

_(Fill these in as you complete chapters — recruiters look for concrete numbers.)_

- Model size: e.g. 124M parameters (GPT-2 small)
- Spam classifier accuracy: e.g. 96%
- Chatbot: fine-tuned to follow instructions on a custom dataset

## Architecture

_(Add a simple diagram of your GPT model here once you reach Chapter 4 — even a hand-drawn sketch or a simple block diagram shows systems thinking.)_

## How to run

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/llm-from-scratch.git
   cd llm-from-scratch
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open any chapter's notebook and run it. A Google Colab link is provided in each chapter for GPU-free setup.

## Tech stack

- Python 3.10+
- PyTorch
- tiktoken (byte-pair encoding tokenizer)
- JupyterLab / Google Colab

## Credits

Based on *Build a Large Language Model (From Scratch)* by Sebastian Raschka (Manning, 2024). Official book repo: [rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch).
