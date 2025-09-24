---
title: "AI Newsletter - 2025-09-24"
date: "2025-09-24"
draft: false
tags: ["newsletter", "ai"]
categories: ["Daily"]
---

### Models
ChatGPT, Claude, Claude 4.5 Sonnet, Claude Code, Claude Opus 4.1 Thinking, Claude Sonnet 4 Thinking, Claude's new Code Interpreter, Codex CLI, DeepSeek 3.1, Flash, GPT-5, GPT-5-mini, Gemini 2.5, Gemini 2.5 Flash, Gemini 2.5 Pro, Gemini 3.0 Pro, Gemini Nano, Gemma, Grok 4 Fast, Kimi K2 0905, Llama 3.2, Moondream 3, Qwen, iOS 26 Apple Foundation model
### Companies
Ambient, Angel Squad, Anthropic, Apple, Brightwave, Canva, DPD, Databricks, DeepSeek, ElevenLabs, Factory, Glean, Google, Happenstance, Howie, Hustle Fund, Inngest, Kimi, Luma Labs, Monologue, Notion, Nvidia, OpenAI, Perplexity, Scale AI, SpaceX, The Economist, Vercel, xAI
### People
Adrien Grondin, Alex Hern, Ben, Julie Zhuo, Keshav, Mr Willison, Naveen, Piotr Grabowski, Piotr Migdał, Yohei
### Products/Tools
AI customer-service bot, AI mode, ARM64, Ambient, Angel Squad, Ben’s Bites, Brightwave (AI investment research platform), Code Interpreter, CompileBench, Completions API, Droid, Factory (CLI tool Droid), Gemini sidebar, GitHub, Glean:LIVE, Go, Google Chrome, Howie, LLM gateway, Locally AI, MCP, MLX, MagicPath Libraries, Notion AI, OpenAI Go library, Orchids, Perplexity Email Assistant, Pyodide, Python, Ray 3, Research a Person on Happenstance, Responses API, SWE-Bench Pro, Vercel Agent, X CRM, bash shell, gucr, iOS, run_terminal_cmd, step.run, tldraw SDK 4.0, ubuntu-22.04-amd64


## Articles

- [CompileBench: Can AI Compile 22-year-old Code?](https://simonwillison.net/2025/Sep/22/compilebench/#atom-tag) — CompileBench is a new LLM benchmark by Piotr Grabowski and Piotr Migdał that evaluates models' ability to compile legacy code, exemplified by cross-compiling 'gucr' for ARM64. The benchmark, which allows three attempts, shows Claude Opus 4.1 Thinking leading with a 100% success rate, followed by Claude Sonnet 4 Thinking and GPT-5 at 93%. GPT-5-mini demonstrates strong value-for-money, while Gemini 2.5 underperforms. The authors emphasize a minimal, model-agnostic benchmark design, implemented with a Go-based harness that utilizes a single `run_terminal_cmd` tool for executing bash commands.

- [Locally AI](https://simonwillison.net/2025/Sep/21/locally-ai/#atom-tag) — The article introduces "Locally AI," a new iOS app by Adrien Grondin that enables users to run various large language models (LLMs) directly on their iPhones. The app recently added immediate support for the iOS 26 Apple Foundation model, allowing instant conversations without additional downloads. It also leverages MLX to support other model families, including Gemma, Llama 3.2, and Qwen. The author also lists recent articles covering topics like the definition of AI agents, a review of Claude's new Code Interpreter, and recreating an AI adoption chart using GPT-5, Python, and Pyodide.

- [Why AI systems might never be secure](https://simonwillison.net/2025/Sep/23/why-ai-systems-might-never-be-secure/#atom-tag) — This article, drawing from a piece in The Economist featuring AI Writer Alex Hern, argues that AI systems, especially Large Language Models (LLMs), may never be secure due to a "lethal trifecta" of conditions, primarily the vulnerability to prompt injection. It highlights that these issues, identified even before ChatGPT's public release, have already led to real-world abuses, such as DPD's AI customer-service bot being exploited. Mr Willison expresses concern that the industry is not taking these risks seriously, instead deploying more powerful, similarly vulnerable tools, suggesting that only a significant financial loss might prompt a change in approach.

- [Grok has a chance](https://www.bensbites.com/p/grok-has-a-chance) — This newsletter highlights significant advancements and updates in the AI/ML landscape. Key news includes xAI's new Grok 4 Fast model, which boasts performance comparable to Gemini 2.5 Pro at a lower price point and a vast context window, alongside rumors of upcoming Gemini 3.0 Pro and Claude 4.5 Sonnet releases. Google Chrome is set to integrate extensive AI features, including a Gemini sidebar, AI-powered address bar searches, and enhanced scam protections using Gemini Nano. Notion is also expanding its AI capabilities with personal and custom agents. The newsletter further covers a range of new AI tools, developer resources, the Moondream 3 vision model's impressive image reasoning abilities, Scale AI's SWE-Bench Pro benchmark, and notable investment news involving ElevenLabs and Nvidia's commitment to OpenAI.