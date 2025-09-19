---
title: "AI Newsletter - 2025-09-19"
date: "2025-09-19"
draft: false
tags: ["newsletter", "ai"]
categories: ["Daily"]
---

### Models
ChatGPT, Claude, Codex, GPT-4, GPT-5, GPT-5-Codex, GPT-5-Pro, Gemini Deep Think, Veo3, experimental reasoning model
### Companies
AWS, Anthropic, Attio, Factory, Flatfile, Github, Google, Granola, Makerpad, Meta, Modal, NVIDIA, OpenAI, Product Hunt, YouTube, Zapier
### People
Adam, Keshav, Shanice
### Products/Tools
AWS Trainium, Ben's Bites Fund II, CLI, CLI agents, Code Interpreter, GitHub, Github CoPilot, Google TPUs, ICPC World Finals, JAX, Linear, NVIDIA GPUs, OpenAI's o3, Pyodide, Python, Ray-Ban glasses, Slack, Twitter, calendar, email


## Articles

- [My announcement](https://www.bensbites.com/p/my-announcement) — The author, an exited founder of Makerpad and investor, announces his new role as Head of Developer Relations at Factory, an AI company focused on agent-native coding tools, emphasizing his belief in technical enablement over traditional coding in the AI era. He will continue investing in AI developer tools via Ben's Bites Fund II and maintain his AI newsletter's broad industry coverage. The article also provides key AI industry updates, including new 'thinking' intensity levels for ChatGPT, GPT-5 and Gemini Deep Think's strong performance in a college-level programming contest, OpenAI's stance on user privacy and safety, Meta's new AI-enabled Ray-Ban glasses, and YouTube's upcoming AI tools like Veo3 for Shorts, alongside a sponsored mention of Attio, an AI-native CRM.

- [Coding as the epicenter of AI progress and the path to general agents](https://www.interconnects.ai/p/coding-as-the-epicenter-of-ai-progress) — The article posits that coding is the most tractable and general domain for continued progress in frontier AI models, offering consistent, meaningful improvements from basic function completion to building complex codebases. It highlights the growing utility of command-line AI agents for rapidly developing mini-projects, a use-case often overlooked by the public due to a disconnect between marketing about "superhuman coding" achievements (like GPT-5's ICPC performance) and the more mundane, scoped application of these agents. Ultimately, the piece argues that these models are delivering increasing practical value to a broader audience, with coding being the most tangible way to experience AI's advancements.

- [Anthropic: A postmortem of three recent issues](https://simonwillison.net/2025/Sep/17/anthropic-postmortem/#atom-tag) — Anthropic recently published a detailed postmortem addressing three infrastructure bugs that intermittently degraded Claude's response quality between August and early September. The company emphasized that quality is never reduced due to demand or server load, attributing the issues solely to these bugs. The complexity was compounded by deploying Claude across multiple hardware platforms, including AWS Trainium, NVIDIA GPUs, and Google TPUs, each requiring specific optimizations. Anthropic also noted that their stringent privacy practices, while protecting users, presented challenges in investigating and reproducing the reported bugs due to limited access to user interactions. Python and JAX are utilized in their serving layer, as illustrated by a TPU-specific bug example.