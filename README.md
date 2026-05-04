## Fernando Conde

AI & Automation Strategist researching what AI platforms actually do during your sessions — and building tools to measure it.

### Current Work

**[HAR-Based AI Platform Forensics](https://github.com/conde-fc/har-forensics)** — Tools and documentation for examining AI platform behavior using standard browser developer tools (F12/DevTools). Covers Claude, ChatGPT, Gemini, Grok, DeepSeek, and Perplexity. Includes per-platform field path references, Python scripts for parsing HAR files and SSE streams, a field classification registry covering 3,919 unique fields, and a redaction toolkit for safe public sharing.

**[Multi-Turn AI Interaction Research Framework](https://github.com/conde-fc/ai-interaction-safety-specs)** — Measurement infrastructure for evaluating AI assistant behaviors across extended conversations. Built from analysis of 900+ sessions and 21M+ words of longitudinal interaction data across multiple platforms. Defines 95+ validated behavioral mechanisms across 6 pattern categories, 15 clinical distress pathways mapped to established psychological constructs, and a 10-dimension evaluation rubric scoring agency support versus agency drift. Licensed under CC BY-NC 4.0.

### What Connects Them

The forensics toolkit captures what platforms are doing at the infrastructure level — system prompts, experiments, model switches, capacity changes. The interaction research framework measures what those dynamics produce at the behavioral level — how multi-turn patterns accumulate to affect user cognition and agency over time. One reveals the architecture. The other measures its effects.

### Coming Later This Year

Evaluation frameworks and measurement tools for quantifying AI behavioral patterns at scale — including detection methods for specification failures, silent regressions, and undisclosed limitations across platforms.

### Background

After studying AI systems for over three years—not as a developer, but as a user systematically documenting thousands of interactions across every major platform—I have found something that changed how I work with these tools entirely.

The core of it is this: these systems generate probable text. They do not verify it. There is no internal mechanism that distinguishes between a true statement and a plausible one. The system produces what fits the context. Whether it is correct is a separate question the architecture has no way to answer. The researchers who built this technology documented this property themselves. The training process optimizes for human preference, not for accuracy. Preference and accuracy are often aligned—and when they are, the tool works beautifully. When they diverge, the tool will confidently produce what satisfies rather than what is correct, with no internal flag marking the difference.

I learned this not from papers initially, but from watching the same patterns repeat across conversations. The system claims a task is complete when it is not. It claims to have read a file and produces specific details that the file does not contain. When I correct it, it agrees eloquently—and then repeats the same class of error moments later. If I press harder, the corrections become more sophisticated while the behavior remains unchanged. The agreement is real in form but does not produce lasting change, because each response begins fresh from the same foundations.

The panel some platforms label "thinking" or "reasoning" is itself generated output, not a window into actual computation. The paper that introduced this technique used the word "mimics" deliberately. The relationship between the displayed reasoning and the underlying process remains, in the authors' own words, an open question. I treat the thinking panel as additional context, not as verification.

What changed for me was accepting that the verification responsibility rests with me—not as a flaw in the tool, but as a property of how it is built. So I verify before proceeding, checking one concrete claim before using any output. When I receive a completion claim, I test it rather than trust it. After a correction, I test immediately, knowing that agreement language does not guarantee behavioral change. When specific numbers appear with confident framing, I ask how they were derived. If no method is described, the numbers were likely generated, not measured. And when I notice I am spending more time correcting than progressing, I reset—starting a fresh conversation with the benefit of what I learned.

These are not technical skills. They are habits of interaction that emerged from observing how the system actually behaves rather than how it is presented. They work across platforms because the underlying architecture is shared. They do not require understanding the internals. They only require accepting what the system's own published research says about its nature, and adjusting accordingly.

The tool is useful. I use it regularly. I simply use it with the understanding that its outputs are generated, not verified—and that the difference between the two is where my attention belongs.

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fernando-conde-fc)
