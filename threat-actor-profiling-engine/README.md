![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen?style=flat-square)
![Tested](https://img.shields.io/badge/Tested%20On-Claude%20%7C%20ChatGPT-blueviolet?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Cybersecurity-red?style=flat-square)

# Threat Actor Profiling Engine

> Build a structured threat actor intelligence profile using the Diamond Model

---

## Overview

This prompt guides an AI assistant through a structured threat actor profiling engine workflow.
It collects all required context through intake questions before generating output,
and breaks the deliverable into labeled sections that can be reviewed one at a time.

**Skills demonstrated:** CTI analysis, Diamond Model, MITRE ATT&CK, structured analytic techniques

---

## Prompt Engineering Highlights

- Role framing sets the AI as a domain expert before any output is generated
- Structured intake collects all required context upfront
- Section-by-section output allows review and revision at each stage
- Safety gates and authorization checks are built into sensitive workflows
- Output is formatted for direct use in tickets, reports, and briefings

---

## Target User

| Attribute | Value |
|---|---|
| Role | SOC analyst, CTI analyst, security engineer |
| Experience level | Entry to mid-level |
| AI platform | Works on Claude, ChatGPT, Gemini (AI-agnostic) |
| Setup required | None — copy, paste, and answer questions |

---

## How to Use

1. Open [`prompt.md`](./prompt.md)
2. Copy everything below the divider line
3. Paste into your AI assistant of choice
4. Answer the intake questions when prompted
5. Review each section before the AI continues to the next

---

## Part of the Cybersecurity AI Prompt Collection

| Prompt | Use Case |
|---|---|
| [Adversary Emulation Planner](../adversary-emulation-planner/) | Purple team emulation plans |
| [Threat Actor Profiling Engine](../threat-actor-profiling-engine/) | CTI threat actor profiles |
| [Threat Hunt Hypothesis Generator](../threat-hunt-hypothesis-generator/) | Threat hunt hypotheses and queries |
| [OSINT Recon Summarizer](../osint-recon-summarizer/) | Attack surface intelligence reports |
| [Security Policy Gap Analyzer](../security-policy-gap-analyzer/) | Compliance gap analysis |
| [Malware Behavior Analyst](../malware-behavior-analyst/) | Malware analysis reports |

---

## License

MIT License — free to use, adapt, and share with attribution.
