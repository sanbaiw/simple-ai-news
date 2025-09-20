---
title: "AI Newsletter - 2025-09-20"
date: "2025-09-20"
draft: false
tags: ["newsletter", "ai"]
categories: ["Daily"]
---

### Models
Claude, Claude Sonnet 4, GPT-5, Gemini
### Companies
Anthropic, GitHub, Gmail, Jira, Notion
### People
Abi Raghuram, Carl Hewitt, Michael Wooldridge
### Products/Tools
Claude's new Code Interpreter, LLM APIs, Notion 3.0 AI Agents, Pyodide, Python, Twitter, function calls, functions.search tool


## Articles

- [I think "agent" may finally have a widely enough agreed upon definition to be useful jargon now](https://simonwillison.net/2025/Sep/18/agents/#atom-tag) — The article argues that the term "agent" in AI engineering has finally coalesced around a useful definition: "An LLM agent runs tools in a loop to achieve a goal." Historically, the term was ambiguous, hindering effective communication, a challenge previously highlighted by Michael Wooldridge in 1994. This refined definition, championed by entities like Anthropic, focuses on an LLM's ability to execute actions via function calls and tools in a bounded process to solve a problem. The author distinguishes this technical understanding from common, often misleading, definitions such as "agents as human replacements," asserting that such concepts remain science fiction due to the lack of accountability in current AI systems.

- [The Hidden Risk in Notion 3.0 AI Agents: Web Search Tool Abuse for Data Exfiltration](https://simonwillison.net/2025/Sep/19/notion-lethal-trifecta/#atom-tag) — A critical security vulnerability has been identified in Notion 3.0's new AI agents, enabling prompt injection data exfiltration through a "lethal trifecta attack." Reported by Abi Raghuram, the attack exploits Notion's AI agent (specifically using Claude Sonnet 4) by leveraging hidden text in a PDF. This tricks the agent into extracting sensitive data, concatenating it, and then exfiltrating the information by constructing a malicious URL that is queried via Notion's `functions.search` tool. This allows private team data to be stolen if users are lured into summarizing seemingly innocent PDFs. A proposed short-term fix involves disabling URL support within Notion's `functions.search()` function, with other Notion integrations also posing potential exfiltration risks.