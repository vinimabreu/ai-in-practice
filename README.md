# Artificial Intelligence in Practice

A free, 84-page handbook on applied AI. Written for developers and technical people who want to actually build with LLMs instead of just reading about them.

**[Download the PDF](Artificial_Intelligence_in_Practice.pdf)**

## Why I wrote this

Most AI content is either academic theory or hype. When I was helping people around me get started, I could not find one practical text that walked from "what is a token" all the way to "here is a working agent with tools, and here is what it costs to run". So I wrote it.

Everything in the book was tested by hand. Prices and version numbers were verified in mid-2026 and will age, so always confirm against official sources before spending money or shipping to production.

## What is inside

The book is progressive. Each part builds on the previous one.

**Foundations**
- AI, machine learning and LLMs: how the pieces fit
- Tokens, context windows, temperature and model parameters
- Setting up a real dev environment: VS Code, terminal, Python, virtual environments
- Claude Code and editor integration

**Running models locally**
- Ollama: installing, essential commands, measuring tokens per second
- The 2026 open-model landscape and which family fits which task
- Sizing hardware: quantization levels, dedicated GPUs, Apple Silicon unified memory
- Visual front ends: Open WebUI, LM Studio, AnythingLLM

**RAG**
- The problem RAG solves and the full pipeline, step by step
- Embeddings and vector databases explained without hand-waving
- Chunking, source quality, reducing hallucinations
- When RAG is the wrong answer

**Agents**
- Chat vs agent: the agent loop
- CrewAI: anatomy of an agent, tasks, crews, sequential vs hierarchical
- Tools: file access, web browsing, controlling a real browser, turning your own code into a tool
- LangChain, LangGraph and LangSmith, and how to choose
- MCP: what problem it solves and how agents from different frameworks work together

**Going deeper**
- Fine-tuning vs RAG: the decisive question, and why LoRA changed the game
- Cost: local vs API, real Anthropic API prices, the hybrid strategy
- Security and privacy: the real risks of autonomous agents and defense principles
- Prompting: the four pillars, few-shot, chain-of-thought, structured JSON output
- Evaluation: what to measure, the AI-judge technique, observability

**Three capstone projects**
- A document Q&A assistant (RAG, with and without code)
- A research agent crew (CrewAI)
- From project to product

## Who it is for

- Developers who have not built with LLMs yet
- Technical people deciding between local models and APIs
- Anyone who wants one coherent path instead of fifty scattered tutorials

If you already run agents in production, parts of this will be review. The evaluation and cost chapters may still be worth your time.

## A warning about the code

The code examples are didactic. They show the logic of each tool. Libraries like CrewAI and LangChain change their syntax often, so test every snippet in your own environment before using it professionally.

## License

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Share it, translate it, adapt it, use it to teach. Just credit the source, keep it non-commercial, and share adaptations under the same license.

## Author

Vinicius Pereira
[github.com/vinimabreu](https://github.com/vinimabreu) · [dev.to/vinimabreu](https://dev.to/vinimabreu)

If the book helped you, a star on this repo helps other people find it.
