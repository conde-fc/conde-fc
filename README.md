## Fernando Conde

AI & Automation Strategist researching what AI platforms actually do during your sessions — and building tools to measure it.

### Current Work

**[HAR-Based AI Platform Forensics](https://github.com/conde-fc/har-forensics)** — Tools and documentation for examining AI platform behavior using standard browser developer tools (F12/DevTools). Covers Claude, ChatGPT, Gemini, Grok, DeepSeek, and Perplexity. Includes per-platform field path references, Python scripts for parsing HAR files and SSE streams, a field classification registry covering 3,919 unique fields, and a redaction toolkit for safe public sharing.

### What I Found

By capturing and analyzing network traffic from six AI platforms, I documented how system prompts compete with user instructions at a 50:1 token ratio, how A/B experiments change model behavior without disclosure, how models switch silently mid-conversation, and how capacity limits change between sessions without notification. Every finding is reproducible using standard browser developer tools. Full methodology and step-by-step replication procedures are in the repo.

### Coming Later This Year

Evaluation frameworks and measurement tools for quantifying AI behavioral patterns at scale — including detection methods for specification failures, silent regressions, and undisclosed limitations across platforms.

### Background

I build production automation systems and AI governance tooling. My work spans regulatory analysis, document processing pipelines, and enterprise workflow automation, with a consistent focus on data sovereignty, local processing, and auditable systems.
